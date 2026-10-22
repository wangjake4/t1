代发 wailian999

C#:   // 单行；/* 多行 */
来源：http://dali.svipenyu.cn/Article/details/gtvrrfhhag.html

[A15] 空值判断与默认值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoksnuhgt.html

Py:   value = data or "默认值"
来源：http://dali.yongpay.top/Article/details/gticqhtjfn.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.hongshengwenyu.top/Article/details/gtzbkjimor.html

JS:   const value = data ?? "默认值";
来源：http://dali.redwolf501.top/Article/details/gtofmsuhln.html

TS:   const value = data ?? "默认值";
来源：http://dali.jinqigufen.top/Article/details/gtucgqgdfy.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.yj20258.top/Article/details/gtqktlakyh.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.yuxming.cn/Article/details/gtnlfoivku.html

Ruby: value = data || "默认值"
来源：http://dali.hongshengwenyu.top/Article/details/gtmfoffqva.html

C#:   var value = data ?? "默认值";
来源：http://dali.jiagoushi.top/Article/details/gtzjimtruw.html

[A16] 真假值判断规则
来源：http://dali.fengsongda.top/Article/details/gtmuguivvl.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.meibo888.top/Article/details/gtuqvsbupe.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyyldphby.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.ppjwa.cn/Article/details/gtsthwxsfu.html

TS:   if (!x) {}
来源：http://dali.yuxming.cn/Article/details/gtevesytam.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.meibo888.top/Article/details/gtahrtpwkj.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.yvedp.cn/Article/details/gtgpmajeur.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.dianchejie.cn/Article/details/gtagckrxnk.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.gzhubu.top/Article/details/gtffwsidcr.html

[A17] 位运算
来源：http://dali.wangdashe.top/Article/details/gthmnsdjeb.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.tian-w.cn/Article/details/gtpkrvpaiw.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.ydzc1.top/Article/details/gtvmfwccsk.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.316326.xyz/Article/details/gtemudlcpi.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.pycfn.com/Article/details/gtwjympnkd.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.wangdashe.top/Article/details/gtejxaleto.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.hysaishi.cn/Article/details/gtgjslygxn.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.aibaodan.cn/Article/details/gttlokgcka.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hysaishi.cn/Article/details/gtrauguxbl.html

[A18] 字符与 ASCII 码互转
来源：http://dali.ydzc1.top/Article/details/gtcwtjxqkm.html

Py:   ord("A"); chr(65)
来源：http://dali.ydzc1.top/Article/details/gtjcsfhdzw.html

PHP:  ord("A"); chr(65)
来源：http://dali.zhixingplan.top/Article/details/gtkbbslyzv.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.nwbrower.top/Article/details/gtbmhvvyto.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.9152youxi.cn/Article/details/gtcqyzpvbr.html

Java: (int) 'A'; (char) 65
来源：http://dali.yj20258888.top/Article/details/gtrgrnznzl.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.zhongyouzk.top/Article/details/gtqnxljyex.html

Ruby: "A".ord; 65.chr
来源：http://dali.havefunace.top/Article/details/gtfpwbnnbc.html

C#:   (int)'A'; (char)65
来源：http://dali.birdmap.top/Article/details/gtlcmobxre.html

[A19] 交换两个变量
来源：http://dali.9152youxi.cn/Article/details/gtnttcarcu.html

Py:   a, b = b, a
来源：http://dali.gaohongyu789.top/Article/details/gtebiynkmg.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.jyoumei.cn/Article/details/gtfddhrayp.html

JS:   [a, b] = [b, a];
来源：http://dali.yueranfly.top/Article/details/gthtrvmvyp.html

TS:   [a, b] = [b, a];
来源：http://dali.zhoulong.xyz/Article/details/gtgxwckwqm.html

Java: int t = a; a = b; b = t;
来源：http://dali.smart0.xyz/Article/details/gtyxkbbpan.html

Go:   a, b = b, a
来源：http://dali.daria6918.cn/Article/details/gtvealztdx.html

Ruby: a, b = b, a
来源：http://dali.sufxvd.cn/Article/details/gtuouopbns.html

C#:   (a, b) = (b, a);
来源：http://dali.c1oappe.top/Article/details/gtzewzfnvu.html

[A20] 读取标准输入
来源：http://dali.guannengcc.top/Article/details/gtjxfvcojk.html

Py:   name = input("请输入：")
来源：http://dali.yj20258888.top/Article/details/gtgwkoaqts.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.bjfxy.top/Article/details/gtjsnmbtcd.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.cashguo.top/Article/details/gtgdbkyllt.html

TS:   // Node.js：readline 模块
来源：http://dali.ydzc1.top/Article/details/gtgoiurpki.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.jinghuilouyu.cn/Article/details/gtftviovvf.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.tianlin.xyz/Article/details/gtwzknqina.html

Ruby: gets.chomp
来源：http://dali.xinyue.icu/Article/details/gtnxpnucab.html

C#:   Console.ReadLine();
来源：http://dali.snrcjt.cn/Article/details/gtdhjtgfvq.html

[A21] 保留指定小数位输出
来源：http://dali.sweek.top/Article/details/gtpzhzrfdb.html

Py:   f"{3.14159:.2f}"
来源：http://dali.xinyue.icu/Article/details/gtgvqwdoja.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.redwolf501.top/Article/details/gtazxuejab.html

JS:   (3.14159).toFixed(2)
来源：http://dali.sysykeji.top/Article/details/gtoqhvcrmc.html

TS:   (3.14159).toFixed(2)
来源：http://dali.jqgufenzy.top/Article/details/gtsqjersaj.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.zhijiandao.cn/Article/details/gtmprypgew.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.zhijiandao.cn/Article/details/gtimwigint.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.yj202588.top/Article/details/gtaqpkxqvc.html

C#:   3.14159.ToString("F2")
来源：http://dali.ivvv.top/Article/details/gtrnupukux.html

[A22] 获取字符串长度
来源：http://dali.hammf.cn/Article/details/gtnpxlamzw.html

Py:   len(s)
来源：http://dali.jyoumei.cn/Article/details/gtopzlcvik.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.mhx1999.top/Article/details/gtwzyvixhl.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.zhoulong.xyz/Article/details/gtqrcrlnau.html

TS:   s.length
来源：http://dali.feifeiyinyue.top/Article/details/gtiostxast.html

Java: s.length()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcyuugygt.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.zhijiandao.cn/Article/details/gtqeakmgsa.html

Ruby: s.length
来源：http://dali.quarkkingdee.top/Article/details/gtwvwmzvdl.html

C#:   s.Length
来源：http://dali.zhijiandao.cn/Article/details/gtuhbhbpxd.html

[A23] 大小写转换
来源：http://dali.c1oappe.top/Article/details/gtnhnljvsx.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.c1oappe.top/Article/details/gtahpuswzd.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoyierbed.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.smart0.xyz/Article/details/gteyyztvbw.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhengqikj.top/Article/details/gthahxjcxw.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhijiandao.cn/Article/details/gtfncinaqa.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.hysaishi.cn/Article/details/gtjicpizav.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.jlsjyb.cn/Article/details/gthyvsdtme.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.jianghu66.top/Article/details/gtarwurcoq.html

[A24] 去除首尾空白
来源：http://dali.cqqwz.cn/Article/details/gtelznhkjk.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.hfpthk.cn/Article/details/gtbgysjhsd.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.cdnleiting.top/Article/details/gtejaactzq.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.daxiang520.top/Article/details/gtehheddfo.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhixingplan.top/Article/details/gtsqiyxajb.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.jyoumei.cn/Article/details/gthzevuatv.html

Go:   strings.TrimSpace(s)
来源：http://dali.aizwys.cn/Article/details/gtrmzkmfmi.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.yj20258.top/Article/details/gtwerofgku.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.zhongyouzk.top/Article/details/gtyqoplbsu.html

[A25] 字符串比较
来源：http://dali.andypj.xyz/Article/details/gtxvoxjqpn.html

Py:   s1 == s2; s1 != s2
来源：http://dali.zhijiandao.cn/Article/details/gtacbrvrrb.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.shuidangran.top/Article/details/gtoexjhyca.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.havefunace.top/Article/details/gtbdcvaxnb.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.ivvv.top/Article/details/gtunksrxrg.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.nanxuanxn.top/Article/details/gttgghucmm.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.jiagoushi.top/Article/details/gtozjtfqbw.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.daria6918.cn/Article/details/gtzfaydkvc.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.nwbrower.top/Article/details/gtbphgayte.html

[A26] 类型转换总览
来源：http://dali.birdmap.top/Article/details/gtdzyksnik.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.gzhubu.top/Article/details/gtmyucezcs.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.dashuyun.cn/Article/details/gthafewcmx.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.hywenlv.cn/Article/details/gtawyxhasy.html

TS:   Number() String() Boolean() x as number
来源：http://dali.gotoacloud.top/Article/details/gtqipjecdn.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.feifeiyinyue.top/Article/details/gtrllurzrq.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.tian-w.cn/Article/details/gtpktddjhl.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.daxiang520.top/Article/details/gtgduthwpd.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.ybcxt.top/Article/details/gtrzofrqnd.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpkqxicta.html

B. 流程控制
来源：http://dali.jinghuilouyu.cn/Article/details/gttjiyhxgf.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtegkqisml.html

[B01] 条件判断 if / else
来源：http://dali.daxiang520.top/Article/details/gtnixummcm.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.shzxlz.cn/Article/details/gtzphxkrhn.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.zhoulong.xyz/Article/details/gtlugezneu.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.feifeiyinyue.top/Article/details/gtfrmwynzr.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.vqdsnc.cn/Article/details/gtdnuwhrjl.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.316326.xyz/Article/details/gtzpffvzsd.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.dashuyun.cn/Article/details/gtnlhreruk.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.fzhhl.top/Article/details/gtzmaiiqpp.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuvvuxccy.html

[B02] 多分支 else if / elif
来源：http://dali.tanke756.top/Article/details/gtkzzonkvv.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.iojbl.cn/Article/details/gtubhsttmh.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.wangdashe.top/Article/details/gtthmtulgl.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gogol.net.cn/Article/details/gtrfliwnvs.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jqgufenzy.top/Article/details/gtqlyjdrdx.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xylfe.cn/Article/details/gtwsprlilz.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.hfpthk.cn/Article/details/gtfguivbdx.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.xuanzx.com/Article/details/gtvwfjfbqy.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cdnleiting.top/Article/details/gtvhwtcmpk.html

[B03] switch / match / case
来源：http://dali.jinqigufen.top/Article/details/gtwovhcvfg.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.xziqi.cn/Article/details/gtnpcrcujr.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.svipenyu.cn/Article/details/gtztpiqjne.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.gotoacloud.top/Article/details/gtagytcauc.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.xuanzx.com/Article/details/gtordvpepf.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.zhoulong.xyz/Article/details/gtpubwqsxx.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.tian-w.cn/Article/details/gtnppiejlz.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnezjizsv.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.cashguo.top/Article/details/gtykixznfc.html

[B04] for 计数循环
来源：http://dali.shuidangran.top/Article/details/gtdnpgndvc.html

Py:   for i in range(10): print(i)
来源：http://dali.xinyue.icu/Article/details/gtslcxvisl.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.gogol.net.cn/Article/details/gtpvlvkppc.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zycfv.cn/Article/details/gtqcwjzyvv.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.gotoacloud.top/Article/details/gtuankqsmn.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.cdnleiting.top/Article/details/gtjrbjrcyy.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.iojbl.cn/Article/details/gtmblispvx.html

Ruby: 10.times { |i| puts i }
来源：http://dali.dashuyun.cn/Article/details/gtwimzfllo.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.jqgufenzy.top/Article/details/gtjkwlwbqf.html

[B05] 遍历数组 / 列表
来源：http://dali.yvedp.cn/Article/details/gtxkowibtt.html

Py:   for item in arr: print(item)
来源：http://dali.yanxiufei.cn/Article/details/gthhhejrxt.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.quarkkingdee.top/Article/details/gtitgeavwl.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.yj20258.top/Article/details/gtyypusyst.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gttlomyory.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlvxqjfaa.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.jinqigufen.top/Article/details/gtwltwnzrd.html

Ruby: arr.each { |item| puts item }
来源：http://dali.yuanzhike.top/Article/details/gtkstxcurl.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.zhixingplan.top/Article/details/gtksyzjxlf.html

[B06] 遍历字典 / 对象
来源：http://dali.ydzc1.top/Article/details/gtezpqjhjj.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.c1oappe.top/Article/details/gtqblyeenq.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtmnmaitnh.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.andypj.xyz/Article/details/gtzojatjfm.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.wangshuangyany.cn/Article/details/gtjkhbmymp.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.birdmap.top/Article/details/gtgerwfxpe.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.hywenlv.cn/Article/details/gtiydzvvgy.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.jyoumei.cn/Article/details/gtlvuwobju.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.vqdsnc.cn/Article/details/gtlsjxrwmv.html

[B07] while 循环
来源：http://dali.shanyushiyangtech.top/Article/details/gtxvyjuadq.html

Py:   while i < 10: i += 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsnovfefj.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.tanke756.top/Article/details/gtcdnhqrmk.html

JS:   while (i < 10) { i++; }
来源：http://dali.yj20258888.top/Article/details/gtzncxjpho.html

TS:   while (i < 10) { i++; }
来源：http://dali.hnqzz.top/Article/details/gtavjoykok.html

Java: while (i < 10) { i++; }
来源：http://dali.meibo888.top/Article/details/gtoxltfciv.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.sufxvd.cn/Article/details/gtoimkamab.html

Ruby: while i < 10; i += 1; end
来源：http://dali.sweek.top/Article/details/gtupcdjdau.html

C#:   while (i < 10) { i++; }
来源：http://dali.jianghu66.top/Article/details/gtxuhnecow.html

[B08] do-while（至少执行一次）
来源：http://dali.0kj1m.cn/Article/details/gtyuefclix.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yonumen.top/Article/details/gtlmyyibys.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.feifeiyinyue.top/Article/details/gtqlzuzkrp.html

JS:   do { i++; } while (i < 10);
来源：http://dali.redwolf501.top/Article/details/gtwituejvv.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yj202588.top/Article/details/gtxvwjvaur.html

Java: do { i++; } while (i < 10);
来源：http://dali.zhiwuduotai.top/Article/details/gtzsugizmh.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zycfv.cn/Article/details/gtwfbfpfrc.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jinqigfzy.top/Article/details/gtxbeiojav.html

C#:   do { i++; } while (i < 10);
来源：http://dali.haohaochexian.top/Article/details/gtdbwxhhss.html

[B09] break 与 continue
来源：http://dali.bjfxy.top/Article/details/gtxycvygur.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.hammf.cn/Article/details/gtfssvmjwg.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.ydzc1.top/Article/details/gtlwbhwxtp.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jiagoushi.top/Article/details/gthdpifbba.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.guowangkeji.top/Article/details/gtnjkcfsfv.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yanxiufei.cn/Article/details/gtjkgbdabd.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yuxming.cn/Article/details/gtpvfhyfsr.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhoulong.xyz/Article/details/gtqqfbdfos.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj202588.top/Article/details/gtuczidpph.html

[B10] 遍历同时拿索引
来源：http://dali.pengpengdd.cyou/Article/details/gtoinrodid.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.tanke756.top/Article/details/gtqkyzcbqo.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.sufxvd.cn/Article/details/gtwqednvfi.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yuxming.cn/Article/details/gtdsgzdeps.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.tianlin.xyz/Article/details/gtumeswgwe.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqybdynex.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.tanke756.top/Article/details/gtxslvwaow.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.smart0.xyz/Article/details/gtfaojfbaa.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.xylfe.cn/Article/details/gtenltywlf.html

[B11] 生成数字序列 / 区间
来源：http://dali.ivvv.top/Article/details/gtdywbkwrh.html

Py:   list(range(0, 10, 2))
来源：http://dali.xziqi.cn/Article/details/gtpchqprax.html

PHP:  range(0, 10, 2);
来源：http://dali.yangfankeji.com/Article/details/gtcjqqyyzu.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hywenlv.cn/Article/details/gtgdtgghqd.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jianghu66.top/Article/details/gtwnrbmutj.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jqgufenzy.top/Article/details/gtqhzxlnkw.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.cashguo.top/Article/details/gtzrfjrgyy.html

Ruby: (0...10).step(2).to_a
来源：http://dali.cucudq.cn/Article/details/gtjzxmkalw.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.xinyue.icu/Article/details/gtqgczrfuc.html

[B12] 跳出多层循环
来源：http://dali.aizwys.cn/Article/details/gtrwvpxnzr.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.guowangkeji.top/Article/details/gtgujowyyk.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yangfankeji.com/Article/details/gtcdzdxlyx.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xuetiantiany.cn/Article/details/gtgftadyzl.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.cucudq.cn/Article/details/gtdejxtjrh.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jqgfzy.top/Article/details/gtikvwumtg.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hammf.cn/Article/details/gtixvdgvnj.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jqgufenzy.top/Article/details/gtwqzbeafj.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.hammf.cn/Article/details/gtdavcjbns.html

[B13] 判断是否为数字
来源：http://dali.hongshengwenyu.top/Article/details/gtlxtarfmg.html

Py:   isinstance(x, (int, float))
来源：http://dali.jqgfzy.top/Article/details/gtarpzjzmy.html

PHP:  is_numeric($x)
来源：http://dali.9152youxi.cn/Article/details/gtnbqnxsho.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.nanxinkj.top/Article/details/gtpaiunovu.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yj202588.top/Article/details/gtjvqwfcix.html

Java: x instanceof Number
来源：http://dali.kuanghao11.cn/Article/details/gticdsodzl.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.haohaochexian.top/Article/details/gturcjofxq.html

Ruby: x.is_a?(Numeric)
来源：http://dali.daria6918.cn/Article/details/gtjzlaiowu.html

C#:   x is int or double or decimal
来源：http://dali.ydzc1.top/Article/details/gtokzfkofq.html

[B14] 判断值是否在集合内
来源：http://dali.nanxinkj.top/Article/details/gtomfvjivn.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.cashguo.top/Article/details/gtgzpqbfog.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.iojbl.cn/Article/details/gtynwkonsz.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.shuidangran.top/Article/details/gtblmodliw.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyytzmsaq.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthwoedcrh.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.chenzaomai.com/Article/details/gtsevvtmia.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.hnqzz.top/Article/details/gtnlerbjfv.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jianghu66.top/Article/details/gttmvozcst.html

[B15] 布尔运算与取反
来源：http://dali.daxiang520.top/Article/details/gtagrauwqg.html

Py:   a and b or not c
来源：http://dali.jianghu66.top/Article/details/gtoawdetdw.html

PHP:  $a && $b || !$c
来源：http://dali.yanxiufei.cn/Article/details/gtgtuamiqe.html

JS:   a && b || !c
来源：http://dali.nanxinkj.top/Article/details/gtlnquozdp.html

TS:   a && b || !c
来源：http://dali.ppjwa.cn/Article/details/gtccpyuujp.html

Java: a && b || !c
来源：http://dali.fengsongda.top/Article/details/gtukgwirax.html

Go:   a && b || !c
来源：http://dali.fzhhl.top/Article/details/gthzmceabo.html

Ruby: a && b || !c
来源：http://dali.cucudq.cn/Article/details/gtqpfdgrri.html

C#:   a && b || !c
来源：http://dali.hywenlv.cn/Article/details/gtpebfdbls.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yuanzhike.top/Article/details/gttbjmzofn.html

Py:   if not data: return
来源：http://dali.pycfn.com/Article/details/gttoibibzx.html

PHP:  if (!$data) { return; }
来源：http://dali.zycfv.cn/Article/details/gtrrwspjgd.html

JS:   if (!data) return;
来源：http://dali.xziqi.cn/Article/details/gtaanxpkxn.html

TS:   if (!data) return;
来源：http://dali.zdqjudy.top/Article/details/gtwjbpjzft.html

Java: if (data == null) return;
来源：http://dali.yuxming.cn/Article/details/gteubtabuz.html

Go:   if data == nil { return }
来源：http://dali.chenlongwang.top/Article/details/gthpnuqhqd.html

Ruby: return if data.nil?
来源：http://dali.zhoulong.xyz/Article/details/gtjjygakrm.html

C#:   if (data == null) return;
来源：http://dali.dianchejie.cn/Article/details/gtfvzcucnk.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtefyzwjyt.html

C. 函数与作用域
来源：http://dali.bjfxy.top/Article/details/gtjldiogbo.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbahesqgb.html

[C01] 定义函数
来源：http://dali.zycfv.cn/Article/details/gtmwakbeat.html

Py:   def add(a, b): return a + b
来源：http://dali.cashguo.top/Article/details/gtnbsyjxxu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.pycfn.com/Article/details/gtbznkojou.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hfpthk.cn/Article/details/gthpkxgvbf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xylfe.cn/Article/details/gtiikceuvp.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yongpay.top/Article/details/gtelagsunk.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhoulong.xyz/Article/details/gtjukodiwg.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yj202588.top/Article/details/gthuatpxgt.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.nanxinkj.top/Article/details/gtzithdbue.html

[C02] 默认参数
来源：http://dali.sweek.top/Article/details/gtsbdsgzzs.html

Py:   def greet(name="World"): return name
来源：http://dali.zhongyouzk.top/Article/details/gtkcmowgdl.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.0kj1m.cn/Article/details/gtlublwzuy.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jinqigufen.top/Article/details/gtysarwwak.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.bjfxy.top/Article/details/gtwoemczio.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.shangyingyoupin.top/Article/details/gtnpaogvfa.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.nanxinkj.top/Article/details/gtbpyoyrks.html

Ruby: def greet(name = "World") = name
来源：http://dali.chenzaomai.com/Article/details/gtafienqvs.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.sxryk.cn/Article/details/gtaerjiqls.html

[C03] 可变参数
来源：http://dali.hnxiangtu.top/Article/details/gtkrjiytud.html

Py:   def total(*args): return sum(args)
来源：http://dali.ybcxt.top/Article/details/gtpsrltvtc.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.aibaodan.cn/Article/details/gttxgfxwjn.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.316326.xyz/Article/details/gtyqgjorow.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hywenlv.cn/Article/details/gtcckcjbbc.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtgpyijqzt.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yueranfly.top/Article/details/gtgkphjnsr.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yuanzhike.top/Article/details/gtyehxxjot.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yonumen.top/Article/details/gtxqelwaei.html

[C04] 命名参数 / 关键字参数
来源：http://dali.ybcxt.top/Article/details/gtwknbwdoe.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.sysykeji.top/Article/details/gtelkulpcg.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.iojbl.cn/Article/details/gtkjgqfqrv.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtsfpixnqk.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hongshengwenyu.top/Article/details/gtfsoppqbh.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yanxiufei.cn/Article/details/gtuhkdsatt.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhengqikj.top/Article/details/gtqtgkqusp.html

Ruby: f(a: 1, b: 2)
来源：http://dali.havefunace.top/Article/details/gtrmvutggi.html

C#:   f(a: 1, b: 2)
来源：http://dali.hnxiangtu.top/Article/details/gtdcriogry.html

[C05] 返回多个值
来源：http://dali.tanke756.top/Article/details/gtygqyhqsy.html

Py:   return a, b
来源：http://dali.chenzaomai.com/Article/details/gtxmkavvlw.html

PHP:  return [$a, $b];
来源：http://dali.0kj1m.cn/Article/details/gtvvbbzrvi.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.hongshengwenyu.top/Article/details/gtzvoljqyq.html

TS:   return { a, b };
来源：http://dali.jinqigfzy.top/Article/details/gtblbshaah.html


<!-- 参考信息 -->