代发 wailian999

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.chenlongwang.top/Article/details/gt2kztfsabi.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qubnehyt.html

TS:   // Node.js：readline 模块
来源：http://dali.chenlongwang.top/Article/details/gt2uaxarren.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.hongshengwenyu.top/Article/details/gt2ipsfrjnw.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.snrcjt.cn/Article/details/gt2wbjgojcr.html

Ruby: gets.chomp
来源：http://dali.vqdsnc.cn/Article/details/gt2nqsuojkk.html

C#:   Console.ReadLine();
来源：http://dali.quarkkingdee.top/Article/details/gt2wcbgqlus.html

[A21] 保留指定小数位输出
来源：http://dali.xziqi.cn/Article/details/gt2osduoqgm.html

Py:   f"{3.14159:.2f}"
来源：http://dali.birdmap.top/Article/details/gt2qftmkaov.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.yuxming.cn/Article/details/gt2vtjreyrg.html

JS:   (3.14159).toFixed(2)
来源：http://dali.hysaishi.cn/Article/details/gt2aegbtfkw.html

TS:   (3.14159).toFixed(2)
来源：http://dali.daxiang520.top/Article/details/gt2uqdxvwcl.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.ybcxt.top/Article/details/gt2aouwmdcr.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.ybcxt.top/Article/details/gt2kfowqecg.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.kuanghao11.cn/Article/details/gt2flyfrqwg.html

C#:   3.14159.ToString("F2")
来源：http://dali.tian-w.cn/Article/details/gt2csbmayoa.html

[A22] 获取字符串长度
来源：http://dali.tian-w.cn/Article/details/gt2bzszxwlm.html

Py:   len(s)
来源：http://dali.birdmap.top/Article/details/gt2lgyosyri.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.jqgufenzy.top/Article/details/gt2svgxsdeh.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.gzhubu.top/Article/details/gt2lygpxvfl.html

TS:   s.length
来源：http://dali.feifeiyinyue.top/Article/details/gt2pmvguqkj.html

Java: s.length()
来源：http://dali.gzhubu.top/Article/details/gt2hjjscpiy.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.hysaishi.cn/Article/details/gt2papsyzpq.html

Ruby: s.length
来源：http://dali.cucudq.cn/Article/details/gt2wkypvaum.html

C#:   s.Length
来源：http://dali.birdmap.top/Article/details/gt2rcwkqdku.html

[A23] 大小写转换
来源：http://dali.fengsongda.top/Article/details/gt2yczjkfgl.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.pengpengdd.cyou/Article/details/gt2eztpgzoy.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.xziqi.cn/Article/details/gt2ovrvetcy.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2grcskbqg.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.aizwys.cn/Article/details/gt2dkactkii.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.hywenlv.cn/Article/details/gt2uzltmwka.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.ppjwa.cn/Article/details/gt2wizddsea.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.ydzc1.top/Article/details/gt2pidcidyx.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.fengsongda.top/Article/details/gt2dgtxyite.html

[A24] 去除首尾空白
来源：http://dali.bjfxy.top/Article/details/gt2fpdlkaad.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.nanxuanxn.top/Article/details/gt2ahpzloap.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.sysykeji.top/Article/details/gt2gqijltte.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.haohaochexian.top/Article/details/gt2tkfpebbt.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.cucudq.cn/Article/details/gt2ktkntvss.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.xinyue.icu/Article/details/gt2kvjarmek.html

Go:   strings.TrimSpace(s)
来源：http://dali.sweek.top/Article/details/gt2bldawhqg.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.hnqzz.top/Article/details/gt2gtasrivm.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.guowangkeji.top/Article/details/gt2lvujwddt.html

[A25] 字符串比较
来源：http://dali.jiagoushi.top/Article/details/gt2fwzgljwl.html

Py:   s1 == s2; s1 != s2
来源：http://dali.zhixingplan.top/Article/details/gt2gacntarx.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.gaohongyu789.top/Article/details/gt2ebjahcsc.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qswyevdc.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.0kj1m.cn/Article/details/gt2zinacgrb.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.zhoulong.xyz/Article/details/gt2wkvjowwh.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.guowangkeji.top/Article/details/gt2gkqumfbs.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.nanxuanxn.top/Article/details/gt2wyjwpozn.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.chenzaomai.com/Article/details/gt2ghnnvnah.html

[A26] 类型转换总览
来源：http://dali.fzhhl.top/Article/details/gt2koroxgjn.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.zycfv.cn/Article/details/gt2xmbyebaz.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.chenzaomai.com/Article/details/gt2vncgcmtx.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nyypfodv.html

TS:   Number() String() Boolean() x as number
来源：http://dali.ydzc1.top/Article/details/gt2ffonxxjk.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.redwolf501.top/Article/details/gt2vpenssla.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.tian-w.cn/Article/details/gt2eivkfwjd.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.hysaishi.cn/Article/details/gt2blkwyrwr.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.316326.xyz/Article/details/gt2sqsnbvaw.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2kivycnyv.html

B. 流程控制
来源：http://dali.yangfankeji.com/Article/details/gt2jiaznlra.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2xtnjgecg.html

[B01] 条件判断 if / else
来源：http://dali.0kj1m.cn/Article/details/gt2qjwoeabg.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.sufxvd.cn/Article/details/gt2ojdxocer.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.yuxming.cn/Article/details/gt2chvnuoxn.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.cheryme.top/Article/details/gt2zuzakacj.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hysaishi.cn/Article/details/gt2esfmhscd.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.jqgfzy.top/Article/details/gt2lqtxugjk.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.aibaodan.cn/Article/details/gt2mjdvbwfm.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.vqdsnc.cn/Article/details/gt2kylfmrvr.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.hammf.cn/Article/details/gt2iqurdyau.html

[B02] 多分支 else if / elif
来源：http://dali.zhijiandao.cn/Article/details/gt2dgsojylh.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hqbatgkv.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.guowangkeji.top/Article/details/gt2uepfqvai.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jqgfzy.top/Article/details/gt2quhcjhgw.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jqgufenzy.top/Article/details/gt2lzlasabq.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ppjwa.cn/Article/details/gt2utepqlkl.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.jiagoushi.top/Article/details/gt2adyrzefm.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.fengsongda.top/Article/details/gt2zznerzbq.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.bjfxy.top/Article/details/gt2banrvqel.html

[B03] switch / match / case
来源：http://dali.pycfn.com/Article/details/gt2pebiuqiz.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.0kj1m.cn/Article/details/gt2iqothhrl.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.xuanzx.com/Article/details/gt2twmdnxio.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jqgfzy.top/Article/details/gt2caudncld.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.cucudq.cn/Article/details/gt2ektbxtvj.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.shzxlz.cn/Article/details/gt2eluwktkm.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.ivvv.top/Article/details/gt2jmmddlvi.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.quarkkingdee.top/Article/details/gt2mkawgbgn.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.tian-w.cn/Article/details/gt2rutmsdjn.html

[B04] for 计数循环
来源：http://dali.jlsjyb.cn/Article/details/gt2pxjgikyw.html

Py:   for i in range(10): print(i)
来源：http://dali.gotoacloud.top/Article/details/gt2tswyrbqo.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2myptjhuh.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.aizwys.cn/Article/details/gt2hhestmyc.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.xziqi.cn/Article/details/gt2socejxlw.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.chenlongwang.top/Article/details/gt2wbxpymzx.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.cqqwz.cn/Article/details/gt2traryurd.html

Ruby: 10.times { |i| puts i }
来源：http://dali.tian-w.cn/Article/details/gt2gmhvebzk.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jwniqfwp.html

[B05] 遍历数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2tctofgpj.html

Py:   for item in arr: print(item)
来源：http://dali.yueranfly.top/Article/details/gt2vigdnfcg.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2tozylzvx.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.tanke756.top/Article/details/gt2iinmfysa.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.dianchejie.cn/Article/details/gt2raswstux.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.hammf.cn/Article/details/gt2yydkevgc.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.jlsjyb.cn/Article/details/gt2anventsn.html

Ruby: arr.each { |item| puts item }
来源：http://dali.ppjwa.cn/Article/details/gt2vnvendfl.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.yuxming.cn/Article/details/gt2njhbqvym.html

[B06] 遍历字典 / 对象
来源：http://dali.jinqigufen.top/Article/details/gt2wbeivkjz.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.chenlongwang.top/Article/details/gt2gqhqsrkp.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.kuanghao11.cn/Article/details/gt2ndwzraiq.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mylafuwg.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.chenzaomai.com/Article/details/gt2rhlwkhzc.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.iojbl.cn/Article/details/gt2cuctddfa.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.aizwys.cn/Article/details/gt2fmcvipvt.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.tianlin.xyz/Article/details/gt2rewfxmzn.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jyoumei.cn/Article/details/gt2qhsvlhry.html

[B07] while 循环
来源：http://dali.jinqigfzy.top/Article/details/gt2yhbrxggt.html

Py:   while i < 10: i += 1
来源：http://dali.cqqwz.cn/Article/details/gt2aoikowem.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2llpqypnj.html

JS:   while (i < 10) { i++; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2aeggzpqw.html

TS:   while (i < 10) { i++; }
来源：http://dali.jyoumei.cn/Article/details/gt2imycqucy.html

Java: while (i < 10) { i++; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2qlqxgmio.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.nanxuanxn.top/Article/details/gt2cbslapbc.html

Ruby: while i < 10; i += 1; end
来源：http://dali.iojbl.cn/Article/details/gt2qchwzonn.html

C#:   while (i < 10) { i++; }
来源：http://dali.andypj.xyz/Article/details/gt2varktcrn.html

[B08] do-while（至少执行一次）
来源：http://dali.ppjwa.cn/Article/details/gt2yalgordu.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.cdnleiting.top/Article/details/gt2pskwyohc.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.cashguo.top/Article/details/gt2udnhtsaa.html

JS:   do { i++; } while (i < 10);
来源：http://dali.cqqwz.cn/Article/details/gt2ychqlmbn.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2npcqcjgr.html

Java: do { i++; } while (i < 10);
来源：http://dali.fzhhl.top/Article/details/gt2rlhcnhgw.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yj20258888.top/Article/details/gt2fnhfrqdq.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.ivvv.top/Article/details/gt2mhwrpfae.html

C#:   do { i++; } while (i < 10);
来源：http://dali.smart0.xyz/Article/details/gt2faqzausp.html

[B09] break 与 continue
来源：http://dali.chenlongwang.top/Article/details/gt2dxgjfdpk.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.c1oappe.top/Article/details/gt2tkayiisv.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.jinqigufen.top/Article/details/gt2mnuwsddm.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2otnogoyf.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hnqzz.top/Article/details/gt2nizkclnf.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2djdermlf.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.316326.xyz/Article/details/gt2zrttzpjp.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yj20258.top/Article/details/gt2ddsfmajz.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylsqafne.html

[B10] 遍历同时拿索引
来源：http://dali.hnqzz.top/Article/details/gt2uxkxzvrc.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yuxming.cn/Article/details/gt2ynxrqssc.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2pqpqyhtt.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.shuidangran.top/Article/details/gt2jzxgeods.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.daxiang520.top/Article/details/gt2lermzscj.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.sxryk.cn/Article/details/gt2zwubrgzd.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yueranfly.top/Article/details/gt2krnuktsb.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.sxryk.cn/Article/details/gt2nrvndmzp.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.iojbl.cn/Article/details/gt2fedbnnyv.html

[B11] 生成数字序列 / 区间
来源：http://dali.cucudq.cn/Article/details/gt2iwbqziht.html

Py:   list(range(0, 10, 2))
来源：http://dali.daria6918.cn/Article/details/gt2clljbuil.html

PHP:  range(0, 10, 2);
来源：http://dali.jianghu66.top/Article/details/gt2fznnsmck.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yj202588.top/Article/details/gt2zzomtlul.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yanxiufei.cn/Article/details/gt2erkywwhw.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.smart0.xyz/Article/details/gt2pvueqtab.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jinqigufen.top/Article/details/gt2lvlkckll.html

Ruby: (0...10).step(2).to_a
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bhodwzfe.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.gotoacloud.top/Article/details/gt2taaersvm.html

[B12] 跳出多层循环
来源：http://dali.shangyingyoupin.top/Article/details/gt2bkoopbmq.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.xuanzx.com/Article/details/gt2qettfaso.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mdyodrfv.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yongpay.top/Article/details/gt2jsjolxnu.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qlpqqodj.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.sysykeji.top/Article/details/gt2iavbaphk.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.guowangkeji.top/Article/details/gt2hhwhgslv.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yj20258.top/Article/details/gt2ketatsrv.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.svipenyu.cn/Article/details/gt2tpqiaqcs.html

[B13] 判断是否为数字
来源：http://dali.ivvv.top/Article/details/gt2rzaahizr.html

Py:   isinstance(x, (int, float))
来源：http://dali.yuxming.cn/Article/details/gt2txkzevau.html

PHP:  is_numeric($x)
来源：http://dali.wangdashe.top/Article/details/gt2tnhqkhwy.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jianghu66.top/Article/details/gt2egqqeofp.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.daxiang520.top/Article/details/gt2reepjrvm.html

Java: x instanceof Number
来源：http://dali.bjfxy.top/Article/details/gt2ceopewcs.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.snrcjt.cn/Article/details/gt2bjtaaycl.html

Ruby: x.is_a?(Numeric)
来源：http://dali.nanxuanxn.top/Article/details/gt2ctjxfvye.html

C#:   x is int or double or decimal
来源：http://dali.ybcxt.top/Article/details/gt2mrehuqne.html

[B14] 判断值是否在集合内
来源：http://dali.zhiwuduotai.top/Article/details/gt2cvdhkavk.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.nanxuanxn.top/Article/details/gt2sofkoebz.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.ppjwa.cn/Article/details/gt2yjtmbhkf.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.tanke756.top/Article/details/gt2lmplygvc.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.hfpthk.cn/Article/details/gt2azickuss.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iqzbgkvi.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.0kj1m.cn/Article/details/gt2tdqjiphb.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.xziqi.cn/Article/details/gt2qwkulznk.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yongpay.top/Article/details/gt2klbxlwbp.html

[B15] 布尔运算与取反
来源：http://dali.gogol.net.cn/Article/details/gt2gvefhusv.html

Py:   a and b or not c
来源：http://dali.vqdsnc.cn/Article/details/gt2ipsfjghi.html

PHP:  $a && $b || !$c
来源：http://dali.aizwys.cn/Article/details/gt2rdwweorr.html

JS:   a && b || !c
来源：http://dali.ehwqpu.com/Article/details/gt2cxcohnwq.html

TS:   a && b || !c
来源：http://dali.fzhhl.top/Article/details/gt2zwpahuwa.html

Java: a && b || !c
来源：http://dali.jinqigufen.top/Article/details/gt2oljruyyn.html

Go:   a && b || !c
来源：http://dali.chenlongwang.top/Article/details/gt2cyyikzhx.html

Ruby: a && b || !c
来源：http://dali.cqqwz.cn/Article/details/gt2nllaerax.html

C#:   a && b || !c
来源：http://dali.hongshengwenyu.top/Article/details/gt2evawnvsl.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jianghu66.top/Article/details/gt2udpgzlrp.html

Py:   if not data: return
来源：http://dali.zhoulong.xyz/Article/details/gt2dbxoquyy.html

PHP:  if (!$data) { return; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2guihhvyq.html

JS:   if (!data) return;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dgsizlwf.html

TS:   if (!data) return;
来源：http://dali.yanxiufei.cn/Article/details/gt2vffinztj.html

Java: if (data == null) return;
来源：http://dali.hammf.cn/Article/details/gt2mvvtwgfx.html

Go:   if data == nil { return }
来源：http://dali.zhixingplan.top/Article/details/gt2zefcfcxs.html

Ruby: return if data.nil?
来源：http://dali.zdqjudy.top/Article/details/gt2oaqyazvv.html

C#:   if (data == null) return;
来源：http://dali.dashuyun.cn/Article/details/gt2cpwshghl.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2wvzhqofb.html

C. 函数与作用域
来源：http://dali.fengsongda.top/Article/details/gt2hmjqxeaq.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2bqrbiltq.html

[C01] 定义函数
来源：http://dali.zhixingplan.top/Article/details/gt2uslgtcfi.html

Py:   def add(a, b): return a + b
来源：http://dali.jlsjyb.cn/Article/details/gt2kzkfaiyd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenlongwang.top/Article/details/gt2ykqgjaac.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.shzxlz.cn/Article/details/gt2aoxzcdtk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ndyghiet.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gt2ilyniban.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jlsjyb.cn/Article/details/gt2vywsypnk.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yangfankeji.com/Article/details/gt2nhdjwoax.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.daxiang520.top/Article/details/gt2mqnqafsq.html

[C02] 默认参数
来源：http://dali.sxryk.cn/Article/details/gt2taljxexf.html

Py:   def greet(name="World"): return name
来源：http://dali.jinqigfzy.top/Article/details/gt2aopvxkyo.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.pycfn.com/Article/details/gt2fndecdqk.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.aibaodan.cn/Article/details/gt2tesaclne.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.ivvv.top/Article/details/gt2gjnuiqqb.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vwdmoeqa.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.smart0.xyz/Article/details/gt2abanwask.html

Ruby: def greet(name = "World") = name
来源：http://dali.mhx1999.top/Article/details/gt2klyyxzde.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rhxksqyt.html

[C03] 可变参数
来源：http://dali.cheryme.top/Article/details/gt2cybhxaev.html

Py:   def total(*args): return sum(args)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gjcetmmk.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhixingplan.top/Article/details/gt2sxawjdpp.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.dashuyun.cn/Article/details/gt2hzflbpdb.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.quarkkingdee.top/Article/details/gt2jgwbqjgx.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.nanxinkj.top/Article/details/gt2cuxxsgtl.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hongshengwenyu.top/Article/details/gt2adzleacg.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.redwolf501.top/Article/details/gt2mambhqmi.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.xziqi.cn/Article/details/gt2sfrkbrkw.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hysaishi.cn/Article/details/gt2fnlhnryh.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.tanke756.top/Article/details/gt2cyjiwpyh.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.nwbrower.top/Article/details/gt2szvchqpv.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhengqikj.top/Article/details/gt2ectmpslk.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yuanzhike.top/Article/details/gt2kstmlpjr.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.shuidangran.top/Article/details/gt2obtotnco.html

Go:   // 无：用配置结构体参数
来源：http://dali.9152youxi.cn/Article/details/gt2ufzmnczb.html

Ruby: f(a: 1, b: 2)
来源：http://dali.sxryk.cn/Article/details/gt2zaicghst.html

C#:   f(a: 1, b: 2)
来源：http://dali.tianlin.xyz/Article/details/gt2bgevubeb.html

[C05] 返回多个值
来源：http://dali.nwbrower.top/Article/details/gt2yjkewzzo.html

Py:   return a, b
来源：http://dali.tanke756.top/Article/details/gt2smemicdc.html

PHP:  return [$a, $b];
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uuejzdcs.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhoulong.xyz/Article/details/gt2qsvjnfdb.html

TS:   return { a, b };
来源：http://dali.gaohongyu789.top/Article/details/gt2srxvwpfc.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.gotoacloud.top/Article/details/gt2nolzydyn.html

Go:   return a, b
来源：http://dali.zycfv.cn/Article/details/gt2nqigpqwz.html

Ruby: return a, b
来源：http://dali.wangdashe.top/Article/details/gt2ntvtzanr.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2augqnxxb.html

[C06] 匿名函数 / lambda
来源：http://dali.chenlongwang.top/Article/details/gt2jqdermac.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2drzxphwa.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.cheryme.top/Article/details/gt2jczkykoe.html

JS:   const square = x => x * x;
来源：http://dali.sysykeji.top/Article/details/gt2xdsaqdtg.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.ydzc1.top/Article/details/gt2xgcevqld.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.bjfxy.top/Article/details/gt2neyuvogk.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.guannengcc.top/Article/details/gt2jywywlyy.html

Ruby: square = ->(x) { x * x }
来源：http://dali.ydzc1.top/Article/details/gt2qdajmhrr.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.cashguo.top/Article/details/gt2gfdcmbkq.html

[C07] 把函数作为参数传入
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iqhpmgnm.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hammf.cn/Article/details/gt2kypagubs.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.ydzc1.top/Article/details/gt2nzeztfwa.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hywenlv.cn/Article/details/gt2piqabcqx.html

TS:   arr.map(String)
来源：http://dali.wangshuangyany.cn/Article/details/gt2pghuaprw.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wfinljcb.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.quarkkingdee.top/Article/details/gt2kquuvaxf.html

Ruby: arr.map(&:upcase)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tyyfdnal.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.sysykeji.top/Article/details/gt2auptnfax.html

[C08] 闭包
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wflrzuvt.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yj20258888.top/Article/details/gt2zvdjjwur.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yj20258888.top/Article/details/gt2rwlwenrj.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yvedp.cn/Article/details/gt2sjvwuans.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.aizwys.cn/Article/details/gt2llymezhu.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yangfankeji.com/Article/details/gt2thonhxes.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yj202588.top/Article/details/gt2wggurqjq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hammf.cn/Article/details/gt2vzumixej.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.hysaishi.cn/Article/details/gt2hymmpadx.html

[C09] 递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iurhqqkl.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jqgufenzy.top/Article/details/gt2xtyihron.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yuxming.cn/Article/details/gt2dczercgs.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.pengpengdd.cyou/Article/details/gt2sjzxodcl.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.bjfxy.top/Article/details/gt2awvumsbk.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.shuidangran.top/Article/details/gt2unjxtunn.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhixingplan.top/Article/details/gt2hdqlcupk.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.ehwqpu.com/Article/details/gt2xcmgpldt.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jinqigfzy.top/Article/details/gt2wiptespd.html

[C10] 变量作用域
来源：http://dali.xinyue.icu/Article/details/gt2vzexvttu.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.nwbrower.top/Article/details/gt2dkldvdpx.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.redwolf501.top/Article/details/gt2iusckvbg.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.andypj.xyz/Article/details/gt2fbnoposq.html

TS:   同 JS
来源：http://dali.0kj1m.cn/Article/details/gt2vdfungrt.html

Java: 方法内为块级作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hsjfjxon.html

Go:   花括号块级作用域
来源：http://dali.shuidangran.top/Article/details/gt2tvmvqkqg.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.cqqwz.cn/Article/details/gt2yrommwex.html


<!-- 参考信息 -->