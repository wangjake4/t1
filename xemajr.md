代发 wailian999

Ruby: a, b = b, a
来源：http://dali.jyoumei.cn/Article/details/gtpomktmgg.html

C#:   (a, b) = (b, a);
来源：http://dali.tian-w.cn/Article/details/gtdcqxyfnc.html

[A20] 读取标准输入
来源：http://dali.ybcxt.top/Article/details/gtmzhgyiub.html

Py:   name = input("请输入：")
来源：http://dali.hammf.cn/Article/details/gtdzsybjax.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.aizwys.cn/Article/details/gtzwpnkvkd.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.shanyushiyangkeji.top/Article/details/gteqrksbvr.html

TS:   // Node.js：readline 模块
来源：http://dali.zdqjudy.top/Article/details/gteidkkcfy.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.shzxlz.cn/Article/details/gteoronfks.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.yuanzhike.top/Article/details/gtljjpwepz.html

Ruby: gets.chomp
来源：http://dali.fzhhl.top/Article/details/gtclqnadpz.html

C#:   Console.ReadLine();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqsqtjmkd.html

[A21] 保留指定小数位输出
来源：http://dali.vqdsnc.cn/Article/details/gtcalnmfcd.html

Py:   f"{3.14159:.2f}"
来源：http://dali.jqgufenzy.top/Article/details/gtaoduqtzv.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.jlsjyb.cn/Article/details/gtoednuigy.html

JS:   (3.14159).toFixed(2)
来源：http://dali.nanxuanxn.top/Article/details/gtgxtvareo.html

TS:   (3.14159).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gtvbziezhz.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.ivvv.top/Article/details/gtavfjxova.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.jianghu66.top/Article/details/gteshnflfa.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.jiagoushi.top/Article/details/gthdxwhllx.html

C#:   3.14159.ToString("F2")
来源：http://dali.feifeiyinyue.top/Article/details/gtgnmffmib.html

[A22] 获取字符串长度
来源：http://dali.xziqi.cn/Article/details/gttersivvu.html

Py:   len(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gteawbkesz.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.hnxiangtu.top/Article/details/gtxsbdamuy.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.xziqi.cn/Article/details/gtihgnladd.html

TS:   s.length
来源：http://dali.xinyue.icu/Article/details/gtyejpugfz.html

Java: s.length()
来源：http://dali.xinyue.icu/Article/details/gtyqbentaq.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.yj202588.top/Article/details/gtiesrygyv.html

Ruby: s.length
来源：http://dali.havefunace.top/Article/details/gtsgkmumwg.html

C#:   s.Length
来源：http://dali.vqdsnc.cn/Article/details/gtddheqdkq.html

[A23] 大小写转换
来源：http://dali.fzhhl.top/Article/details/gthdkjwjkr.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.iojbl.cn/Article/details/gtqbsywfwc.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.chenzaomai.com/Article/details/gtdydyvmnj.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhoulong.xyz/Article/details/gterrjhahy.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yonumen.top/Article/details/gteyiqainm.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.hfpthk.cn/Article/details/gtxyimdxxj.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.jiagoushi.top/Article/details/gthtwzdzlc.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.birdmap.top/Article/details/gtobtiolic.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.cashguo.top/Article/details/gtfbrsrrea.html

[A24] 去除首尾空白
来源：http://dali.dianchejie.cn/Article/details/gtbvgaroeo.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.zhengqikj.top/Article/details/gtceqdjrvd.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.dianchejie.cn/Article/details/gtwgvcglch.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yj202588.top/Article/details/gtisxgsbsg.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yanxiufei.cn/Article/details/gtaajgitcf.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.aizwys.cn/Article/details/gtaodlnewh.html

Go:   strings.TrimSpace(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtfbznklrb.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.ydzc1.top/Article/details/gtvmizqozc.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.tian-w.cn/Article/details/gtqltdybax.html

[A25] 字符串比较
来源：http://dali.sxryk.cn/Article/details/gtaqdjfzdd.html

Py:   s1 == s2; s1 != s2
来源：http://dali.jinqigufen.top/Article/details/gteyxlokek.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.svipenyu.cn/Article/details/gtyaqmbifp.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.redwolf501.top/Article/details/gtjqjmbjec.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.iojbl.cn/Article/details/gtqlwzkcuc.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.nwbrower.top/Article/details/gtcyjaxtxf.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.shangyingyoupin.top/Article/details/gtyqawfcmw.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.zhengqikj.top/Article/details/gtxiumsufp.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.xziqi.cn/Article/details/gttjmrhcdt.html

[A26] 类型转换总览
来源：http://dali.vqdsnc.cn/Article/details/gtjqdjwyzv.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.nwbrower.top/Article/details/gtnhonogxa.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.jyoumei.cn/Article/details/gtgpjxbqac.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.cucudq.cn/Article/details/gtiohvpfss.html

TS:   Number() String() Boolean() x as number
来源：http://dali.fengsongda.top/Article/details/gteapgnagy.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.redwolf501.top/Article/details/gtytcbagwa.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.xziqi.cn/Article/details/gtruwbgmyy.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.gogol.net.cn/Article/details/gtrxcjdxuc.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.zycfv.cn/Article/details/gtsmyaevhn.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtinculnsa.html

B. 流程控制
来源：http://dali.9152youxi.cn/Article/details/gtztpryghr.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtqsacmknr.html

[B01] 条件判断 if / else
来源：http://dali.aibaodan.cn/Article/details/gtbdsopykq.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.iojbl.cn/Article/details/gtwyxymtmv.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtglyafwop.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yonumen.top/Article/details/gtylmppkyk.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.cashguo.top/Article/details/gtxlvcsara.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.cqqwz.cn/Article/details/gtmgtwvqve.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.jiagoushi.top/Article/details/gtduwnuzsy.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.tanke756.top/Article/details/gtyleusccp.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.tanke756.top/Article/details/gtaapcxnrv.html

[B02] 多分支 else if / elif
来源：http://dali.sysykeji.top/Article/details/gtvvuccdpb.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.wangdashe.top/Article/details/gthjvlxxmn.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.yonumen.top/Article/details/gtwxmmgvge.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xziqi.cn/Article/details/gtfqwtpqrp.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hongshengwenyu.top/Article/details/gttmnteedu.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtevcdyuap.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.yj202588.top/Article/details/gtbnbmzjqj.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.sweek.top/Article/details/gtxgfykcla.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hnxiangtu.top/Article/details/gtrvleshsd.html

[B03] switch / match / case
来源：http://dali.sweek.top/Article/details/gtrdmzmgjr.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.shuidangran.top/Article/details/gtczpmnyme.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.guowangkeji.top/Article/details/gtwltrblpk.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.nanxinkj.top/Article/details/gtxmjcgong.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.hywenlv.cn/Article/details/gtbxkbzykh.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.yangfankeji.com/Article/details/gtwvxknwfi.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.redwolf501.top/Article/details/gtioclvwwl.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.yvedp.cn/Article/details/gtkpzsedjf.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.chenzaomai.com/Article/details/gtxvujehjx.html

[B04] for 计数循环
来源：http://dali.yj20258.top/Article/details/gtwztdxplw.html

Py:   for i in range(10): print(i)
来源：http://dali.shanyushiyangtech.top/Article/details/gthmzqcmgi.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.sufxvd.cn/Article/details/gtvnxedisl.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.svipenyu.cn/Article/details/gtgeulckgm.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtruvojaty.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.jinqigufen.top/Article/details/gtussvcpbl.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.vqdsnc.cn/Article/details/gtqrnsexzd.html

Ruby: 10.times { |i| puts i }
来源：http://dali.xuetiantiany.cn/Article/details/gtaefpogzd.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.xinyue.icu/Article/details/gtxibwxvsu.html

[B05] 遍历数组 / 列表
来源：http://dali.jyoumei.cn/Article/details/gtjxhxngmm.html

Py:   for item in arr: print(item)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqblwlmkn.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.pengpengdd.cyou/Article/details/gtmoeweqzb.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.nanxuanxn.top/Article/details/gtxxpjludv.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.xuanzx.com/Article/details/gtoqhhupay.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.wangshuangyany.cn/Article/details/gtawbvxhay.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.zdqjudy.top/Article/details/gttvkcgbuy.html

Ruby: arr.each { |item| puts item }
来源：http://dali.chenlongwang.top/Article/details/gtlpkgctqe.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.redwolf501.top/Article/details/gtqekbqmbe.html

[B06] 遍历字典 / 对象
来源：http://dali.9152youxi.cn/Article/details/gtfjslgsvi.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.shuidangran.top/Article/details/gtwjnyonkf.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.zhixingplan.top/Article/details/gtxsqotlsi.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.gotoacloud.top/Article/details/gteqlftssq.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.pengpengdd.cyou/Article/details/gtpsxovobu.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.shuidangran.top/Article/details/gtnhcgayyt.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.smart0.xyz/Article/details/gtkpdwxxhy.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.zhoulong.xyz/Article/details/gtppnunyev.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.cashguo.top/Article/details/gtpfsldaxt.html

[B07] while 循环
来源：http://dali.yuanzhike.top/Article/details/gtusrkvxms.html

Py:   while i < 10: i += 1
来源：http://dali.sweek.top/Article/details/gtqllmlmhx.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.pengpengdd.cyou/Article/details/gtlzyuzjgf.html

JS:   while (i < 10) { i++; }
来源：http://dali.hnqzz.top/Article/details/gtpiabbjly.html

TS:   while (i < 10) { i++; }
来源：http://dali.ehwqpu.com/Article/details/gtsnsobwaa.html

Java: while (i < 10) { i++; }
来源：http://dali.haohaochexian.top/Article/details/gtrthqyngr.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yj202588.top/Article/details/gtvwpcdfee.html

Ruby: while i < 10; i += 1; end
来源：http://dali.hnxiangtu.top/Article/details/gteejxryty.html

C#:   while (i < 10) { i++; }
来源：http://dali.shzxlz.cn/Article/details/gtdnrcmxts.html

[B08] do-while（至少执行一次）
来源：http://dali.guannengcc.top/Article/details/gtfhfqdbyx.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zhiwuduotai.top/Article/details/gtlfnjraiq.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yongpay.top/Article/details/gtiwymzpjy.html

JS:   do { i++; } while (i < 10);
来源：http://dali.wangshuangyany.cn/Article/details/gtbqajssmc.html

TS:   do { i++; } while (i < 10);
来源：http://dali.cdnleiting.top/Article/details/gtnazlhiaz.html

Java: do { i++; } while (i < 10);
来源：http://dali.xziqi.cn/Article/details/gtnyahdbht.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtazxodesz.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.andypj.xyz/Article/details/gtjwwbzwla.html

C#:   do { i++; } while (i < 10);
来源：http://dali.wangdashe.top/Article/details/gtzrimmqux.html

[B09] break 与 continue
来源：http://dali.jiagoushi.top/Article/details/gtganggsoz.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yj20258888.top/Article/details/gtfdvllhqx.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzlajrbry.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.9152youxi.cn/Article/details/gtdmtuuicq.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hammf.cn/Article/details/gtujzdzewb.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.pycfn.com/Article/details/gtigjtbpwv.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.0kj1m.cn/Article/details/gtapgvqnrv.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvkqkertg.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cashguo.top/Article/details/gtrqyhlapk.html

[B10] 遍历同时拿索引
来源：http://dali.zhongyouzk.top/Article/details/gtdbsgbaip.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.fengsongda.top/Article/details/gtsgsahudt.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.kuanghao11.cn/Article/details/gthaurlwsi.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yongpay.top/Article/details/gtahiuqfiy.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.pengpengdd.cyou/Article/details/gtnvzmqefz.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.andypj.xyz/Article/details/gtnpouomji.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jianghu66.top/Article/details/gtrldhsata.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.0kj1m.cn/Article/details/gtogomfavb.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfcgbcjka.html

[B11] 生成数字序列 / 区间
来源：http://dali.shanyushiyangtech.top/Article/details/gtsayhqdko.html

Py:   list(range(0, 10, 2))
来源：http://dali.yj202588.top/Article/details/gtirokoons.html

PHP:  range(0, 10, 2);
来源：http://dali.svipenyu.cn/Article/details/gtwxownvci.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.sysykeji.top/Article/details/gtppqtljyb.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtggzzrwwx.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.sxryk.cn/Article/details/gtvpuxqzhv.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.andypj.xyz/Article/details/gtsxxgnnax.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhengqikj.top/Article/details/gtofdvrfuk.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhijiandao.cn/Article/details/gtaasxuxqu.html

[B12] 跳出多层循环
来源：http://dali.jinqigufen.top/Article/details/gthnxpelfw.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.ppjwa.cn/Article/details/gtouajzjia.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.xuetiantiany.cn/Article/details/gtqiwbbxsn.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shanyushiyangtech.top/Article/details/gtuuzqlcxm.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.sweek.top/Article/details/gtododhros.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.cqqwz.cn/Article/details/gtdjwwzndy.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.shangyingyoupin.top/Article/details/gtixqdgpmp.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.redwolf501.top/Article/details/gtyseepmax.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jinqigfzy.top/Article/details/gtaimtxfie.html

[B13] 判断是否为数字
来源：http://dali.yanxiufei.cn/Article/details/gtsllrdylq.html

Py:   isinstance(x, (int, float))
来源：http://dali.yuanzhike.top/Article/details/gtiizgpeot.html

PHP:  is_numeric($x)
来源：http://dali.gotoacloud.top/Article/details/gtelzgjljf.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.snrcjt.cn/Article/details/gtmxbrmeop.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtukxcbhfm.html

Java: x instanceof Number
来源：http://dali.zhoulong.xyz/Article/details/gtnlcmpcyx.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.svipenyu.cn/Article/details/gtrfzarlxz.html

Ruby: x.is_a?(Numeric)
来源：http://dali.gzhubu.top/Article/details/gtexkhtrdx.html

C#:   x is int or double or decimal
来源：http://dali.xylfe.cn/Article/details/gtwnkcawsq.html

[B14] 判断值是否在集合内
来源：http://dali.yj20258888.top/Article/details/gtccedrtmv.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhiwuduotai.top/Article/details/gtxphdmxpv.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jqgufenzy.top/Article/details/gtobdwkrfy.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.snrcjt.cn/Article/details/gtihcogcwg.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zycfv.cn/Article/details/gtwmilpgmb.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.haohaochexian.top/Article/details/gttcmdxsfy.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zdqjudy.top/Article/details/gtoocriupj.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yueranfly.top/Article/details/gtmvomqmtv.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.snrcjt.cn/Article/details/gtuuwezvqz.html

[B15] 布尔运算与取反
来源：http://dali.316326.xyz/Article/details/gtoskfaqzf.html

Py:   a and b or not c
来源：http://dali.daxiang520.top/Article/details/gtxxerqeqp.html

PHP:  $a && $b || !$c
来源：http://dali.shanyushiyangtech.top/Article/details/gtgeckhzuh.html

JS:   a && b || !c
来源：http://dali.jinqigfzy.top/Article/details/gtseufwxde.html

TS:   a && b || !c
来源：http://dali.tian-w.cn/Article/details/gtdtyyloyf.html

Java: a && b || !c
来源：http://dali.gotoacloud.top/Article/details/gtudvqgwmm.html

Go:   a && b || !c
来源：http://dali.quarkkingdee.top/Article/details/gtgnildrof.html

Ruby: a && b || !c
来源：http://dali.zhixingplan.top/Article/details/gtpjgvwhmv.html

C#:   a && b || !c
来源：http://dali.hysaishi.cn/Article/details/gtyobgamfw.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.gaohongyu789.top/Article/details/gtustwblys.html

Py:   if not data: return
来源：http://dali.birdmap.top/Article/details/gtiukxmmnn.html

PHP:  if (!$data) { return; }
来源：http://dali.hywenlv.cn/Article/details/gtyndbqkmp.html

JS:   if (!data) return;
来源：http://dali.jiagoushi.top/Article/details/gtgtoerrcz.html

TS:   if (!data) return;
来源：http://dali.svipenyu.cn/Article/details/gtchhnhitj.html

Java: if (data == null) return;
来源：http://dali.bjfxy.top/Article/details/gtlpxlbivj.html

Go:   if data == nil { return }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkjguuquv.html

Ruby: return if data.nil?
来源：http://dali.yuxming.cn/Article/details/gtojwhulyq.html

C#:   if (data == null) return;
来源：http://dali.316326.xyz/Article/details/gtshlgxobf.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtwfcbcjzs.html

C. 函数与作用域
来源：http://dali.sysykeji.top/Article/details/gttlcqwumn.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtnnelrvkc.html

[C01] 定义函数
来源：http://dali.sufxvd.cn/Article/details/gtgbnpfoyn.html

Py:   def add(a, b): return a + b
来源：http://dali.zdqjudy.top/Article/details/gtpeasjkyh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.wangdashe.top/Article/details/gtyrnnjozm.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.pycfn.com/Article/details/gtwddlitru.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.snrcjt.cn/Article/details/gtcrmvzzgt.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yj20258888.top/Article/details/gtisveoyoa.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.mhx1999.top/Article/details/gtxgksqjjw.html

Ruby: def add(a, b); a + b; end
来源：http://dali.guannengcc.top/Article/details/gtbbnnjoen.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yonumen.top/Article/details/gtujemoxfa.html

[C02] 默认参数
来源：http://dali.zhengqikj.top/Article/details/gtdgdskntd.html

Py:   def greet(name="World"): return name
来源：http://dali.yongpay.top/Article/details/gtdbgffmqg.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.316326.xyz/Article/details/gtejcwqqzj.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.smart0.xyz/Article/details/gtigakxlxl.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zdqjudy.top/Article/details/gtcpfcdwbl.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.aibaodan.cn/Article/details/gtldqihydl.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.havefunace.top/Article/details/gtcoxponyr.html

Ruby: def greet(name = "World") = name
来源：http://dali.jinghuilouyu.cn/Article/details/gtkioxahem.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.gotoacloud.top/Article/details/gtjoarepxk.html

[C03] 可变参数
来源：http://dali.mhx1999.top/Article/details/gtfgpfpxsl.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhixingplan.top/Article/details/gtkngnspnq.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yj20258888.top/Article/details/gtcxwargfj.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.snrcjt.cn/Article/details/gtmlutenul.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.daxiang520.top/Article/details/gtgfjcsanb.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yj20258.top/Article/details/gtgmbuifoc.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.gzhubu.top/Article/details/gtpvchrwad.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.feifeiyinyue.top/Article/details/gtpulffjfb.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtypsduemy.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhoulong.xyz/Article/details/gttkrznzvv.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.sxryk.cn/Article/details/gtpgrbjxwc.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.feifeiyinyue.top/Article/details/gtblsuoxdr.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.ppjwa.cn/Article/details/gtszlifemr.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.meibo888.top/Article/details/gtunlrilen.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.cashguo.top/Article/details/gtqtnmemma.html

Go:   // 无：用配置结构体参数
来源：http://dali.zdqjudy.top/Article/details/gtevblpwmh.html

Ruby: f(a: 1, b: 2)
来源：http://dali.smart0.xyz/Article/details/gtkcxhxsdz.html

C#:   f(a: 1, b: 2)
来源：http://dali.gotoacloud.top/Article/details/gthfzpuvrq.html

[C05] 返回多个值
来源：http://dali.chenlongwang.top/Article/details/gteqhkddzk.html

Py:   return a, b
来源：http://dali.hysaishi.cn/Article/details/gthhxcbbbs.html

PHP:  return [$a, $b];
来源：http://dali.hysaishi.cn/Article/details/gtxzfmnjfi.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.andypj.xyz/Article/details/gtorxsgdua.html

TS:   return { a, b };
来源：http://dali.jinqigufen.top/Article/details/gtothgtngt.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ehwqpu.com/Article/details/gtiyxbvyut.html

Go:   return a, b
来源：http://dali.gaohongyu789.top/Article/details/gtdmsdkibw.html

Ruby: return a, b
来源：http://dali.andypj.xyz/Article/details/gthzelezxx.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.0kj1m.cn/Article/details/gtrpbendga.html

[C06] 匿名函数 / lambda
来源：http://dali.dashuyun.cn/Article/details/gtjnknnunj.html

Py:   square = lambda x: x * x
来源：http://dali.zhaomingkeji.xyz/Article/details/gteeujyoac.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hnqzz.top/Article/details/gtlnnpkrgm.html

JS:   const square = x => x * x;
来源：http://dali.ivvv.top/Article/details/gtwpjmdxba.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yonumen.top/Article/details/gtvhymjdvm.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.svipenyu.cn/Article/details/gtrrxxfuet.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhixingplan.top/Article/details/gtrltbhqsf.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yanxiufei.cn/Article/details/gtbulbuybd.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yuxming.cn/Article/details/gtfrpnsbwn.html

[C07] 把函数作为参数传入
来源：http://dali.jqgufenzy.top/Article/details/gtodptnlpu.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.aibaodan.cn/Article/details/gtpqxgtulp.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.xinyue.icu/Article/details/gtjfbpjcpv.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xuanzx.com/Article/details/gtnzhyfumq.html

TS:   arr.map(String)
来源：http://dali.sufxvd.cn/Article/details/gtwmdnqpep.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.cheryme.top/Article/details/gtrzpgncdq.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.ybcxt.top/Article/details/gtmuhmirpp.html

Ruby: arr.map(&:upcase)
来源：http://dali.hysaishi.cn/Article/details/gtytjrcevi.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrruoozxh.html

[C08] 闭包
来源：http://dali.hysaishi.cn/Article/details/gthmvnuink.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlcyplagd.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.quarkkingdee.top/Article/details/gtojqrwdsi.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.haohaochexian.top/Article/details/gthawvamlv.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hongshengwenyu.top/Article/details/gtojrqnsbg.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.316326.xyz/Article/details/gtplhbwigm.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.xinyue.icu/Article/details/gtscobuhht.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.cashguo.top/Article/details/gtzvmvqybi.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpkxvidwx.html

[C09] 递归
来源：http://dali.mhx1999.top/Article/details/gtfjrzlmjr.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.gotoacloud.top/Article/details/gtedkywhnf.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.birdmap.top/Article/details/gtfulmisjt.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtibzyqyjb.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.daria6918.cn/Article/details/gtqcqunemk.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.aizwys.cn/Article/details/gtugtxqtpv.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.nanxinkj.top/Article/details/gtvddmuxeh.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.gogol.net.cn/Article/details/gtglkudgxw.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jiagoushi.top/Article/details/gtmrempwuh.html

[C10] 变量作用域
来源：http://dali.yj20258888.top/Article/details/gtkbjneuvh.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.tian-w.cn/Article/details/gtemvmaolz.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.tanke756.top/Article/details/gtsdnpjuqb.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.chenjidiqi.icu/Article/details/gtgaecngoq.html


<!-- 参考信息 -->