代发 wailian999

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.redwolf501.top/Article/details/gtnktqnxgj.html

Ruby: gets.chomp
来源：http://dali.zdqjudy.top/Article/details/gtjbgqaaii.html

C#:   Console.ReadLine();
来源：http://dali.iojbl.cn/Article/details/gtqrcobedt.html

[A21] 保留指定小数位输出
来源：http://dali.zycfv.cn/Article/details/gtivvmfchf.html

Py:   f"{3.14159:.2f}"
来源：http://dali.daxiang520.top/Article/details/gtfgdqclbl.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.jqgfzy.top/Article/details/gtxfzokxfb.html

JS:   (3.14159).toFixed(2)
来源：http://dali.jiagoushi.top/Article/details/gtrktcrswn.html

TS:   (3.14159).toFixed(2)
来源：http://dali.hnxiangtu.top/Article/details/gttbpkdoix.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.fzhhl.top/Article/details/gtnpzvhkqd.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.gzhubu.top/Article/details/gttpgxampu.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.gaohongyu789.top/Article/details/gtzludducl.html

C#:   3.14159.ToString("F2")
来源：http://dali.kuanghao11.cn/Article/details/gtpiajjsrn.html

[A22] 获取字符串长度
来源：http://dali.hnqzz.top/Article/details/gtyuoevved.html

Py:   len(s)
来源：http://dali.dianchejie.cn/Article/details/gtwrkhmukb.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.bjfxy.top/Article/details/gtjamninoh.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.yanxiufei.cn/Article/details/gttmrmdmja.html

TS:   s.length
来源：http://dali.zhongyouzk.top/Article/details/gtbddotfxp.html

Java: s.length()
来源：http://dali.jinqigufen.top/Article/details/gtjkzwgsht.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.zhengqikj.top/Article/details/gtszudztgl.html

Ruby: s.length
来源：http://dali.xinyue.icu/Article/details/gtkvbbedgp.html

C#:   s.Length
来源：http://dali.tian-w.cn/Article/details/gtnkkrapdu.html

[A23] 大小写转换
来源：http://dali.aibaodan.cn/Article/details/gtrcrvgmen.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpwuooubv.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.haohaochexian.top/Article/details/gtziatuqyy.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.sysykeji.top/Article/details/gteuuyztuz.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jlsjyb.cn/Article/details/gtllisnton.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.jqgfzy.top/Article/details/gtnntinilm.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.zhongyouzk.top/Article/details/gtflcloxdc.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.aibaodan.cn/Article/details/gtqabeulza.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.gzhubu.top/Article/details/gtvxjfprst.html

[A24] 去除首尾空白
来源：http://dali.jinghuilouyu.cn/Article/details/gthimnxvjj.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.yvedp.cn/Article/details/gtfjdkeuld.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.jianghu66.top/Article/details/gtonbvwfyi.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.cheryme.top/Article/details/gtflvuphcc.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.snrcjt.cn/Article/details/gtrvwhjifr.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.hfpthk.cn/Article/details/gtrwrwnjhj.html

Go:   strings.TrimSpace(s)
来源：http://dali.shzxlz.cn/Article/details/gtnrwlwqaj.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.zycfv.cn/Article/details/gtwqvlhgqb.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.gogol.net.cn/Article/details/gtgmihgyis.html

[A25] 字符串比较
来源：http://dali.shzxlz.cn/Article/details/gtrovkomip.html

Py:   s1 == s2; s1 != s2
来源：http://dali.feifeiyinyue.top/Article/details/gtmkqascna.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.guannengcc.top/Article/details/gtmpiwjnna.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.gogol.net.cn/Article/details/gtzaroecup.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.daxiang520.top/Article/details/gtemdzqkuj.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.hfpthk.cn/Article/details/gtnmeuzluh.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.zhoulong.xyz/Article/details/gtopjaqkyb.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.svipenyu.cn/Article/details/gtpzoqhemk.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.tanke756.top/Article/details/gtlyjopnqu.html

[A26] 类型转换总览
来源：http://dali.hywenlv.cn/Article/details/gtowvmufwj.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.shangyingyoupin.top/Article/details/gtzstxgoub.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.guannengcc.top/Article/details/gtrrpjcoto.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.cheryme.top/Article/details/gttaspdolh.html

TS:   Number() String() Boolean() x as number
来源：http://dali.zhixingplan.top/Article/details/gtvzughwxd.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.feifeiyinyue.top/Article/details/gtjlzawwuv.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.hywenlv.cn/Article/details/gttsgsssgj.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.yj20258.top/Article/details/gtcdhwrsco.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.c1oappe.top/Article/details/gtwjcoshfx.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gttfksmsal.html

B. 流程控制
来源：http://dali.gotoacloud.top/Article/details/gtmbwybmkk.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtvffcewih.html

[B01] 条件判断 if / else
来源：http://dali.sxryk.cn/Article/details/gtomthvexc.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.yj202588.top/Article/details/gtqqbmmehq.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.yonumen.top/Article/details/gtjaszgeet.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jinghuilouyu.cn/Article/details/gtvzzndghu.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.gotoacloud.top/Article/details/gttzyetgbp.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.haohaochexian.top/Article/details/gttdvnnfvh.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.yanxiufei.cn/Article/details/gtqlxfidhr.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.cdnleiting.top/Article/details/gtepvawrga.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.dianchejie.cn/Article/details/gtrttmntbz.html

[B02] 多分支 else if / elif
来源：http://dali.pengpengdd.cyou/Article/details/gtyebdcqae.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.zhixingplan.top/Article/details/gtprtcpjts.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.shuidangran.top/Article/details/gtybezopbr.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.daria6918.cn/Article/details/gtbridmfuu.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jiagoushi.top/Article/details/gtljscocrk.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.chenlongwang.top/Article/details/gtoervqmbr.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.vqdsnc.cn/Article/details/gtromgytrz.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.havefunace.top/Article/details/gtjjnjqdev.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.quarkkingdee.top/Article/details/gtufgvtyjy.html

[B03] switch / match / case
来源：http://dali.tian-w.cn/Article/details/gtyfhpyeeg.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.wangshuangyany.cn/Article/details/gtvnrkrjsu.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.hywenlv.cn/Article/details/gtccsofdfk.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtkjwbfoem.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.shuidangran.top/Article/details/gtujqzuysu.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.daxiang520.top/Article/details/gtstnszmzf.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.dianchejie.cn/Article/details/gtbhyazqml.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.zhongyouzk.top/Article/details/gtimgtmbio.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.hongshengwenyu.top/Article/details/gthwxuwqmq.html

[B04] for 计数循环
来源：http://dali.pycfn.com/Article/details/gtqkmscqgz.html

Py:   for i in range(10): print(i)
来源：http://dali.zhongyouzk.top/Article/details/gtvfqfhobp.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.jyoumei.cn/Article/details/gtjfimvipy.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jiagoushi.top/Article/details/gtzrwjevax.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.sxryk.cn/Article/details/gtaasthhxz.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.shangyingyoupin.top/Article/details/gtvfjhhypr.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.aibaodan.cn/Article/details/gtunyplsyg.html

Ruby: 10.times { |i| puts i }
来源：http://dali.ivvv.top/Article/details/gtpvoqaezn.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.zdqjudy.top/Article/details/gtfuzplldi.html

[B05] 遍历数组 / 列表
来源：http://dali.zhiwuduotai.top/Article/details/gtcsilynrr.html

Py:   for item in arr: print(item)
来源：http://dali.yj202588.top/Article/details/gtuzhunrnc.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.yuanzhike.top/Article/details/gtyqvnmveh.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhoulong.xyz/Article/details/gtvkgmsrxx.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.wangshuangyany.cn/Article/details/gtqguhumbd.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.yueranfly.top/Article/details/gtglaeicch.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.jinghuilouyu.cn/Article/details/gtpiojfirp.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zdqjudy.top/Article/details/gttyxmdgvb.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.fzhhl.top/Article/details/gtmmqoktyw.html

[B06] 遍历字典 / 对象
来源：http://dali.andypj.xyz/Article/details/gtwtwnnawa.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.jinqigfzy.top/Article/details/gttqjcvdyv.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.birdmap.top/Article/details/gtnswicooe.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hammf.cn/Article/details/gtchkhvnrk.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.aizwys.cn/Article/details/gtzqovwqas.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.redwolf501.top/Article/details/gtzwmzxkjm.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.shangyingyoupin.top/Article/details/gtkcwrjehf.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.zhijiandao.cn/Article/details/gtvxsjaedp.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtmigkqshq.html

[B07] while 循环
来源：http://dali.aibaodan.cn/Article/details/gtsnxtvfzj.html

Py:   while i < 10: i += 1
来源：http://dali.c1oappe.top/Article/details/gtiujooxku.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.xziqi.cn/Article/details/gtoxnjmzme.html

JS:   while (i < 10) { i++; }
来源：http://dali.yj20258888.top/Article/details/gtspdmkgkq.html

TS:   while (i < 10) { i++; }
来源：http://dali.yonumen.top/Article/details/gttlualyvh.html

Java: while (i < 10) { i++; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtfjbkdqgd.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.birdmap.top/Article/details/gtqknzgtlh.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yuxming.cn/Article/details/gtkpbrhzyy.html

C#:   while (i < 10) { i++; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtevjqhkbw.html

[B08] do-while（至少执行一次）
来源：http://dali.zhijiandao.cn/Article/details/gtwmnmyvhk.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.316326.xyz/Article/details/gtsrykaydf.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.chenzaomai.com/Article/details/gtbpqhfybt.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yangfankeji.com/Article/details/gtivplgbmz.html

TS:   do { i++; } while (i < 10);
来源：http://dali.cashguo.top/Article/details/gtdqrngqzc.html

Java: do { i++; } while (i < 10);
来源：http://dali.chenlongwang.top/Article/details/gtdmseglng.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.ivvv.top/Article/details/gtpquhwzbg.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yj20258888.top/Article/details/gtdzsiwlth.html

C#:   do { i++; } while (i < 10);
来源：http://dali.wangshuangyany.cn/Article/details/gtexdyggir.html

[B09] break 与 continue
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgllrnlxo.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.hongshengwenyu.top/Article/details/gthmzyluul.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.havefunace.top/Article/details/gtamvbwrja.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jqgfzy.top/Article/details/gtdjaivdgr.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shangyingyoupin.top/Article/details/gtpgkoinvq.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.quarkkingdee.top/Article/details/gtzxmddsqj.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.ivvv.top/Article/details/gtopndqjgn.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.cdnleiting.top/Article/details/gtnpnmeyoj.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sweek.top/Article/details/gtnyyxhsxo.html

[B10] 遍历同时拿索引
来源：http://dali.shangyingyoupin.top/Article/details/gtzpeiahee.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.shuidangran.top/Article/details/gtctjboevk.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.haohaochexian.top/Article/details/gtvuowykgk.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yueranfly.top/Article/details/gtxtwsssdz.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.shzxlz.cn/Article/details/gttpyhglnh.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.xuanzx.com/Article/details/gtnpgunfzn.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.birdmap.top/Article/details/gtxqvqlduj.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.bjfxy.top/Article/details/gtsvjqivhz.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.sufxvd.cn/Article/details/gtevtuhjkn.html

[B11] 生成数字序列 / 区间
来源：http://dali.daria6918.cn/Article/details/gtahsgkghb.html

Py:   list(range(0, 10, 2))
来源：http://dali.jinqigfzy.top/Article/details/gtubnvktus.html

PHP:  range(0, 10, 2);
来源：http://dali.gzhubu.top/Article/details/gtbogzcepy.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.0kj1m.cn/Article/details/gtzuruwvun.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ppjwa.cn/Article/details/gtcuscjqsu.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.ppjwa.cn/Article/details/gtrsfesvtw.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.0kj1m.cn/Article/details/gtoqdapvbx.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhijiandao.cn/Article/details/gtpiffbvpa.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.ppjwa.cn/Article/details/gtroiyozsk.html

[B12] 跳出多层循环
来源：http://dali.svipenyu.cn/Article/details/gtxsmycixf.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jinqigufen.top/Article/details/gtflpqdozc.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yongpay.top/Article/details/gtgixtkrza.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqpsshurv.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthatpfkjk.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gtaghrgdak.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.daria6918.cn/Article/details/gtmbovuriu.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.meibo888.top/Article/details/gtixlupsyn.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhengqikj.top/Article/details/gtyqyauuim.html

[B13] 判断是否为数字
来源：http://dali.sysykeji.top/Article/details/gtqahdxzpt.html

Py:   isinstance(x, (int, float))
来源：http://dali.snrcjt.cn/Article/details/gtjkfjfler.html

PHP:  is_numeric($x)
来源：http://dali.yongpay.top/Article/details/gtwywwtaah.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sweek.top/Article/details/gtkfaseqhn.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yuanzhike.top/Article/details/gtcpfzwmfp.html

Java: x instanceof Number
来源：http://dali.tianlin.xyz/Article/details/gtelyoopzx.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yvedp.cn/Article/details/gtvwetcmwq.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yongpay.top/Article/details/gtwdwhzrow.html

C#:   x is int or double or decimal
来源：http://dali.jianghu66.top/Article/details/gtxooiqcql.html

[B14] 判断值是否在集合内
来源：http://dali.nanxinkj.top/Article/details/gtkpvbysnz.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hongshengwenyu.top/Article/details/gtdcrbiroy.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.fengsongda.top/Article/details/gtzslldjno.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jianghu66.top/Article/details/gtgboaehyn.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yuxming.cn/Article/details/gtrsibqyzy.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jlsjyb.cn/Article/details/gtmdmjimaw.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdjbniekm.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.nwbrower.top/Article/details/gtyddaqeqp.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpdytjvho.html

[B15] 布尔运算与取反
来源：http://dali.wangshuangyany.cn/Article/details/gtrvzvsmwf.html

Py:   a and b or not c
来源：http://dali.tanke756.top/Article/details/gtuewgdjaf.html

PHP:  $a && $b || !$c
来源：http://dali.yuanzhike.top/Article/details/gtzlyencoo.html

JS:   a && b || !c
来源：http://dali.jyoumei.cn/Article/details/gtqzpjbphp.html

TS:   a && b || !c
来源：http://dali.svipenyu.cn/Article/details/gtraonaeto.html

Java: a && b || !c
来源：http://dali.zhiwuduotai.top/Article/details/gtyvlcgjtr.html

Go:   a && b || !c
来源：http://dali.hywenlv.cn/Article/details/gtixvueuxl.html

Ruby: a && b || !c
来源：http://dali.xuanzx.com/Article/details/gtohzqkqhj.html

C#:   a && b || !c
来源：http://dali.aibaodan.cn/Article/details/gtwaazkmkb.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yvedp.cn/Article/details/gtpcoorcdb.html

Py:   if not data: return
来源：http://dali.mhx1999.top/Article/details/gtrqcqojlb.html

PHP:  if (!$data) { return; }
来源：http://dali.daxiang520.top/Article/details/gtqaxpixky.html

JS:   if (!data) return;
来源：http://dali.gotoacloud.top/Article/details/gtiszwjrev.html

TS:   if (!data) return;
来源：http://dali.jlsjyb.cn/Article/details/gtrlmpjbhm.html

Java: if (data == null) return;
来源：http://dali.ehwqpu.com/Article/details/gthfpawzjz.html

Go:   if data == nil { return }
来源：http://dali.gogol.net.cn/Article/details/gtfxthudbt.html

Ruby: return if data.nil?
来源：http://dali.yangfankeji.com/Article/details/gtnaxttqae.html

C#:   if (data == null) return;
来源：http://dali.cdnleiting.top/Article/details/gtgjxgenle.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtayfzevpl.html

C. 函数与作用域
来源：http://dali.birdmap.top/Article/details/gthzmpgwtu.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtjezwwlcj.html

[C01] 定义函数
来源：http://dali.guannengcc.top/Article/details/gtnswdzfzp.html

Py:   def add(a, b): return a + b
来源：http://dali.ydzc1.top/Article/details/gtyoezkhup.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gtriblynjg.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtfkjjaibf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gtkizblixa.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.hnxiangtu.top/Article/details/gthigveisf.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcwcvphja.html

Ruby: def add(a, b); a + b; end
来源：http://dali.cheryme.top/Article/details/gtdpfcmpeb.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.andypj.xyz/Article/details/gtogwipkbm.html

[C02] 默认参数
来源：http://dali.hysaishi.cn/Article/details/gtwfdpszkp.html

Py:   def greet(name="World"): return name
来源：http://dali.gzhubu.top/Article/details/gtyzytxgyg.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yj20258888.top/Article/details/gtfhdvuedu.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yj20258.top/Article/details/gtyngoqryj.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.vqdsnc.cn/Article/details/gtrfnozvjs.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.xinyue.icu/Article/details/gtzuzcjmlg.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jlsjyb.cn/Article/details/gtpyeafyzp.html

Ruby: def greet(name = "World") = name
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkbutmiom.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yj20258888.top/Article/details/gthixtagxi.html

[C03] 可变参数
来源：http://dali.tian-w.cn/Article/details/gtlvmqcbfg.html

Py:   def total(*args): return sum(args)
来源：http://dali.gaohongyu789.top/Article/details/gtwhxjnipa.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.nanxinkj.top/Article/details/gtmghbmfni.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.aizwys.cn/Article/details/gtwkucgxbj.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhongyouzk.top/Article/details/gtsayabtcn.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.cqqwz.cn/Article/details/gtezrmdbpv.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.c1oappe.top/Article/details/gtxxpdvnku.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.sysykeji.top/Article/details/gtgxqpfwtz.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.vqdsnc.cn/Article/details/gtmmcsykle.html

[C04] 命名参数 / 关键字参数
来源：http://dali.chenlongwang.top/Article/details/gtfoebgpqu.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yueranfly.top/Article/details/gtogezjzgm.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.gzhubu.top/Article/details/gtbnoejlgf.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gterdfpjjs.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yanxiufei.cn/Article/details/gtkharmcda.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jqgufenzy.top/Article/details/gtttqfzlny.html

Go:   // 无：用配置结构体参数
来源：http://dali.zycfv.cn/Article/details/gtegppyfkm.html

Ruby: f(a: 1, b: 2)
来源：http://dali.haohaochexian.top/Article/details/gtlhsnhkyo.html

C#:   f(a: 1, b: 2)
来源：http://dali.bjfxy.top/Article/details/gtiqratjlz.html

[C05] 返回多个值
来源：http://dali.bjfxy.top/Article/details/gtvflttocn.html

Py:   return a, b
来源：http://dali.yvedp.cn/Article/details/gtjpuhtsqm.html

PHP:  return [$a, $b];
来源：http://dali.xziqi.cn/Article/details/gtfqkrplxd.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.sysykeji.top/Article/details/gtprvkjnom.html

TS:   return { a, b };
来源：http://dali.hywenlv.cn/Article/details/gtgcpvfrsh.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.cashguo.top/Article/details/gtkbnxbmib.html

Go:   return a, b
来源：http://dali.nanxuanxn.top/Article/details/gtgqhazpom.html

Ruby: return a, b
来源：http://dali.9152youxi.cn/Article/details/gtmjgfernh.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.hnxiangtu.top/Article/details/gtfykokrwi.html

[C06] 匿名函数 / lambda
来源：http://dali.cheryme.top/Article/details/gtebfrdbuh.html

Py:   square = lambda x: x * x
来源：http://dali.vqdsnc.cn/Article/details/gtfsjpzwyz.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.wangshuangyany.cn/Article/details/gtlgzaipit.html

JS:   const square = x => x * x;
来源：http://dali.shangyingyoupin.top/Article/details/gtwcwvntyy.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.vqdsnc.cn/Article/details/gtuwtxyqcr.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.chenjidiqi.icu/Article/details/gtewfytges.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.gaohongyu789.top/Article/details/gtmguqyrkb.html

Ruby: square = ->(x) { x * x }
来源：http://dali.tian-w.cn/Article/details/gtrvhttlcr.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.shanyushiyangtech.top/Article/details/gtzfilqjzw.html

[C07] 把函数作为参数传入
来源：http://dali.cucudq.cn/Article/details/gtvidzwhew.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.shangyingyoupin.top/Article/details/gtoyybuzeu.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.nanxinkj.top/Article/details/gtwogbtfdw.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.tanke756.top/Article/details/gtgtyrzdfx.html

TS:   arr.map(String)
来源：http://dali.aizwys.cn/Article/details/gtoearpjay.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.fengsongda.top/Article/details/gtxjufhnxn.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.kuanghao11.cn/Article/details/gtcxxfqbga.html

Ruby: arr.map(&:upcase)
来源：http://dali.fzhhl.top/Article/details/gtlspxruak.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jinghuilouyu.cn/Article/details/gtbyalseui.html

[C08] 闭包
来源：http://dali.jinqigufen.top/Article/details/gttuqrjgsq.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zdqjudy.top/Article/details/gtibpgechm.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yonumen.top/Article/details/gtwfvrmwoe.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.smart0.xyz/Article/details/gtusrhyozm.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.cdnleiting.top/Article/details/gtyndyrmjt.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhengqikj.top/Article/details/gtjhikrqum.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.ydzc1.top/Article/details/gtswwktnle.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.tianlin.xyz/Article/details/gtmyhkzgxx.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jiagoushi.top/Article/details/gtdtrfybot.html

[C09] 递归
来源：http://dali.jinqigfzy.top/Article/details/gtqsjwamvv.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.0kj1m.cn/Article/details/gtsxtufotj.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtfzoqspsg.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.daxiang520.top/Article/details/gtgxgjfrsq.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cucudq.cn/Article/details/gtdceyeyye.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.vqdsnc.cn/Article/details/gtljeyshvh.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yj20258.top/Article/details/gtpttnzxoa.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.cucudq.cn/Article/details/gtqavaiohc.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.chenzaomai.com/Article/details/gtkdmaaegi.html

[C10] 变量作用域
来源：http://dali.yvedp.cn/Article/details/gtqxnvgitm.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlnyeemye.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.birdmap.top/Article/details/gtyxofvjpx.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yuxming.cn/Article/details/gtsfwjbgpw.html

TS:   同 JS
来源：http://dali.guowangkeji.top/Article/details/gtroydhywc.html

Java: 方法内为块级作用域
来源：http://dali.ppjwa.cn/Article/details/gtrnrfzurz.html

Go:   花括号块级作用域
来源：http://dali.xuanzx.com/Article/details/gtcmhrdddy.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.chenzaomai.com/Article/details/gtubemqehr.html

C#:   块级作用域
来源：http://dali.guannengcc.top/Article/details/gtmerhsfil.html

[C11] 模块导入与导出
来源：http://dali.yanxiufei.cn/Article/details/gtxqtcaihn.html

Py:   from module import func
来源：http://dali.zhongyouzk.top/Article/details/gtddouspmj.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.havefunace.top/Article/details/gtjimthita.html


<!-- 参考信息 -->