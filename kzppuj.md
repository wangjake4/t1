代发 wailian999

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.chenzaomai.com/Article/details/gthybcwltg.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.chenzaomai.com/Article/details/gtowsikkga.html

TS:   // Node.js：readline 模块
来源：http://dali.jqgfzy.top/Article/details/gtchznqofk.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.zhengqikj.top/Article/details/gtfzfkmwkl.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.zycfv.cn/Article/details/gtxixirgzy.html

Ruby: gets.chomp
来源：http://dali.yonumen.top/Article/details/gtneirsbbn.html

C#:   Console.ReadLine();
来源：http://dali.sysykeji.top/Article/details/gtiqzqzofx.html

[A21] 保留指定小数位输出
来源：http://dali.jqgufenzy.top/Article/details/gtgltzuvdc.html

Py:   f"{3.14159:.2f}"
来源：http://dali.jyoumei.cn/Article/details/gtzinjwmbh.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.wangdashe.top/Article/details/gtfyoekaeg.html

JS:   (3.14159).toFixed(2)
来源：http://dali.guowangkeji.top/Article/details/gtwelkvcpr.html

TS:   (3.14159).toFixed(2)
来源：http://dali.guannengcc.top/Article/details/gtnyshzxat.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.kuanghao11.cn/Article/details/gtjxgcicrw.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.xziqi.cn/Article/details/gtmoubttsc.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.jinqigufen.top/Article/details/gtvfasrfgv.html

C#:   3.14159.ToString("F2")
来源：http://dali.shanyushiyangtech.top/Article/details/gtvixptzow.html

[A22] 获取字符串长度
来源：http://dali.tanke756.top/Article/details/gtmdwrejgk.html

Py:   len(s)
来源：http://dali.jinqigfzy.top/Article/details/gteswoynwy.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.yueranfly.top/Article/details/gtfvzgesar.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.daria6918.cn/Article/details/gthphoiger.html

TS:   s.length
来源：http://dali.andypj.xyz/Article/details/gtppjecyiv.html

Java: s.length()
来源：http://dali.yueranfly.top/Article/details/gtdytjosio.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.cashguo.top/Article/details/gturwgdxjn.html

Ruby: s.length
来源：http://dali.cucudq.cn/Article/details/gtmzcccvjy.html

C#:   s.Length
来源：http://dali.svipenyu.cn/Article/details/gtbkajzsvq.html

[A23] 大小写转换
来源：http://dali.nwbrower.top/Article/details/gtrqobemkz.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.shangyingyoupin.top/Article/details/gtpnggpieu.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.xuetiantiany.cn/Article/details/gtaucqadou.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.shangyingyoupin.top/Article/details/gtcxkmqmis.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.gzhubu.top/Article/details/gtakgmjwfw.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.ehwqpu.com/Article/details/gtmhquakkv.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.fzhhl.top/Article/details/gtifswleaq.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.gzhubu.top/Article/details/gtvkumehus.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.vqdsnc.cn/Article/details/gthcguoucc.html

[A24] 去除首尾空白
来源：http://dali.birdmap.top/Article/details/gtlhbrghyp.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.snrcjt.cn/Article/details/gthjedzjkc.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.gaohongyu789.top/Article/details/gtqxishifz.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzvlrzisp.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.hnxiangtu.top/Article/details/gtugrukako.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.pengpengdd.cyou/Article/details/gtwakbaoxz.html

Go:   strings.TrimSpace(s)
来源：http://dali.fzhhl.top/Article/details/gtnpnnsjjg.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.sysykeji.top/Article/details/gtdtsnohkh.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.chenzaomai.com/Article/details/gtwbkkjzlj.html

[A25] 字符串比较
来源：http://dali.xylfe.cn/Article/details/gtdddeynri.html

Py:   s1 == s2; s1 != s2
来源：http://dali.cashguo.top/Article/details/gtpqltyxpx.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.daxiang520.top/Article/details/gtxbptdzqj.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.hysaishi.cn/Article/details/gtwwxkmfrq.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yangfankeji.com/Article/details/gtwcluytpe.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.pengpengdd.cyou/Article/details/gtuklzevho.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.redwolf501.top/Article/details/gtjxcjpywn.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.hysaishi.cn/Article/details/gtrdjjaste.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.fzhhl.top/Article/details/gtgggqlbjx.html

[A26] 类型转换总览
来源：http://dali.havefunace.top/Article/details/gtwidpczxd.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.daxiang520.top/Article/details/gthhrerisj.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.guannengcc.top/Article/details/gthhzdfexk.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.ybcxt.top/Article/details/gtknuavanw.html

TS:   Number() String() Boolean() x as number
来源：http://dali.xuetiantiany.cn/Article/details/gtroeuekpp.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.cucudq.cn/Article/details/gtxtqfjivd.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.yuanzhike.top/Article/details/gtuohttfgh.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.redwolf501.top/Article/details/gtfetrasgc.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.0kj1m.cn/Article/details/gtmkqhiwko.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtehqezftn.html

B. 流程控制
来源：http://dali.fzhhl.top/Article/details/gtwbrwlzlp.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtqnsmwpan.html

[B01] 条件判断 if / else
来源：http://dali.hfpthk.cn/Article/details/gtaouixony.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnahteugr.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.nanxuanxn.top/Article/details/gtqbcbqzvz.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.xylfe.cn/Article/details/gtbxbqdvml.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.wangshuangyany.cn/Article/details/gtvpmememb.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.jlsjyb.cn/Article/details/gtxbdsngqj.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.fzhhl.top/Article/details/gtnuabzivf.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.jlsjyb.cn/Article/details/gtjbraxsby.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.meibo888.top/Article/details/gtqxwgnarf.html

[B02] 多分支 else if / elif
来源：http://dali.svipenyu.cn/Article/details/gtowywmpga.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.shzxlz.cn/Article/details/gtlepzmufu.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.hnxiangtu.top/Article/details/gtvmytptno.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.redwolf501.top/Article/details/gtqnwjgbwj.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhoulong.xyz/Article/details/gtghezqolb.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yuxming.cn/Article/details/gtiimntrxv.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.svipenyu.cn/Article/details/gtcioepdfl.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.shuidangran.top/Article/details/gtrucxtzww.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ppjwa.cn/Article/details/gtemgdpzdw.html

[B03] switch / match / case
来源：http://dali.yanxiufei.cn/Article/details/gtlovdfcow.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.chenzaomai.com/Article/details/gtyruflemy.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.mhx1999.top/Article/details/gtlthzstfl.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.cashguo.top/Article/details/gtkenwbfso.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtvnyhkzvm.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.cheryme.top/Article/details/gtnqnzherh.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.yanxiufei.cn/Article/details/gttfkqjshu.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.quarkkingdee.top/Article/details/gteageetti.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.yj20258.top/Article/details/gttmglvzzo.html

[B04] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gthelelevg.html

Py:   for i in range(10): print(i)
来源：http://dali.daria6918.cn/Article/details/gtoynvhbrc.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.zycfv.cn/Article/details/gtcxbxibkw.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.havefunace.top/Article/details/gtforstkwl.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.gzhubu.top/Article/details/gtvibwyuww.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.yonumen.top/Article/details/gtrsqnlqkp.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.sweek.top/Article/details/gtphhnmzmd.html

Ruby: 10.times { |i| puts i }
来源：http://dali.cashguo.top/Article/details/gtywzhxkhj.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.9152youxi.cn/Article/details/gtputvtane.html

[B05] 遍历数组 / 列表
来源：http://dali.fengsongda.top/Article/details/gtpkjtcybg.html

Py:   for item in arr: print(item)
来源：http://dali.bjfxy.top/Article/details/gtqbntkgqw.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.shangyingyoupin.top/Article/details/gtgkkstjxy.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtougvluhz.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.wangshuangyany.cn/Article/details/gtlgcmzehu.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.ydzc1.top/Article/details/gtydjudcjd.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.sysykeji.top/Article/details/gtvlizorua.html

Ruby: arr.each { |item| puts item }
来源：http://dali.cheryme.top/Article/details/gthsyhritd.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.fzhhl.top/Article/details/gtjzwwbchi.html

[B06] 遍历字典 / 对象
来源：http://dali.dianchejie.cn/Article/details/gtqgweslsu.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.snrcjt.cn/Article/details/gtmduikbkl.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.cdnleiting.top/Article/details/gtaztjscse.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.vqdsnc.cn/Article/details/gtcwcilpqb.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hnqzz.top/Article/details/gtztfzitcy.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.chenlongwang.top/Article/details/gtifcrjkjd.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtynnfgeiz.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.sweek.top/Article/details/gtzysethgn.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.hywenlv.cn/Article/details/gtqizaiofo.html

[B07] while 循环
来源：http://dali.nanxinkj.top/Article/details/gtfbhkqgmf.html

Py:   while i < 10: i += 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtiqvwonqa.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgkkqxvxm.html

JS:   while (i < 10) { i++; }
来源：http://dali.yj20258.top/Article/details/gtkkvxkmmx.html

TS:   while (i < 10) { i++; }
来源：http://dali.jlsjyb.cn/Article/details/gtusxzvvif.html

Java: while (i < 10) { i++; }
来源：http://dali.ydzc1.top/Article/details/gtuyysxihu.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yanxiufei.cn/Article/details/gtpxawqrih.html

Ruby: while i < 10; i += 1; end
来源：http://dali.shzxlz.cn/Article/details/gthhgpiggf.html

C#:   while (i < 10) { i++; }
来源：http://dali.fzhhl.top/Article/details/gtvfbywocb.html

[B08] do-while（至少执行一次）
来源：http://dali.redwolf501.top/Article/details/gtiffbrpcg.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjfiwzzft.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yonumen.top/Article/details/gtsbyrgecu.html

JS:   do { i++; } while (i < 10);
来源：http://dali.tian-w.cn/Article/details/gtquvrdwdc.html

TS:   do { i++; } while (i < 10);
来源：http://dali.hnxiangtu.top/Article/details/gtdhiurasj.html

Java: do { i++; } while (i < 10);
来源：http://dali.yanxiufei.cn/Article/details/gtkxkipztl.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.xuanzx.com/Article/details/gtyjrgbcge.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yuxming.cn/Article/details/gtuadlfjst.html

C#:   do { i++; } while (i < 10);
来源：http://dali.ydzc1.top/Article/details/gtqwopqmxx.html

[B09] break 与 continue
来源：http://dali.havefunace.top/Article/details/gtxcuhxojs.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.snrcjt.cn/Article/details/gteyejvpbf.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.daxiang520.top/Article/details/gtnbowqjif.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xylfe.cn/Article/details/gtytnegdhk.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jqgfzy.top/Article/details/gtilonunpa.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj202588.top/Article/details/gtdcpimcgj.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.havefunace.top/Article/details/gttkhfgxju.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhengqikj.top/Article/details/gtntzbvynz.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yanxiufei.cn/Article/details/gtvhwlzpar.html

[B10] 遍历同时拿索引
来源：http://dali.fengsongda.top/Article/details/gtlgwislbf.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.haohaochexian.top/Article/details/gtddtjwfjv.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.smart0.xyz/Article/details/gtuygxbtep.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.havefunace.top/Article/details/gtetpzkcqm.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.chenlongwang.top/Article/details/gtwhatltsg.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtyxnebota.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.vqdsnc.cn/Article/details/gtnpwaydgo.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yj20258.top/Article/details/gturjihulw.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.shangyingyoupin.top/Article/details/gtnufchqkw.html

[B11] 生成数字序列 / 区间
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlzhrxkox.html

Py:   list(range(0, 10, 2))
来源：http://dali.yj202588.top/Article/details/gtomfkarcx.html

PHP:  range(0, 10, 2);
来源：http://dali.zdqjudy.top/Article/details/gtgebweukt.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.vqdsnc.cn/Article/details/gtbtpaloxp.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.guannengcc.top/Article/details/gthrbuoyvl.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.dianchejie.cn/Article/details/gthpcjwmvc.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.iojbl.cn/Article/details/gtvhxvvftg.html

Ruby: (0...10).step(2).to_a
来源：http://dali.gogol.net.cn/Article/details/gtheqrsyah.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.hammf.cn/Article/details/gtwcavpaub.html

[B12] 跳出多层循环
来源：http://dali.zhijiandao.cn/Article/details/gtdyexgwqg.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.fengsongda.top/Article/details/gtzgorwzid.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.birdmap.top/Article/details/gtifkoqgsg.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xziqi.cn/Article/details/gtrdpdbubk.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jqgfzy.top/Article/details/gtyywcdcat.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhongyouzk.top/Article/details/gtniketkdu.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthxmszqzg.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.daria6918.cn/Article/details/gtuvafgguf.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.tian-w.cn/Article/details/gtjcvvqrqa.html

[B13] 判断是否为数字
来源：http://dali.ybcxt.top/Article/details/gtzgabwilq.html

Py:   isinstance(x, (int, float))
来源：http://dali.yongpay.top/Article/details/gtlqtvlhxq.html

PHP:  is_numeric($x)
来源：http://dali.jiagoushi.top/Article/details/gtmvjkfcrk.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.andypj.xyz/Article/details/gthstfkffs.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.nwbrower.top/Article/details/gttdctxual.html

Java: x instanceof Number
来源：http://dali.yuxming.cn/Article/details/gtsklwhden.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.shuidangran.top/Article/details/gtdfethila.html

Ruby: x.is_a?(Numeric)
来源：http://dali.gogol.net.cn/Article/details/gtztaebnne.html

C#:   x is int or double or decimal
来源：http://dali.hysaishi.cn/Article/details/gtzwzmzszj.html

[B14] 判断值是否在集合内
来源：http://dali.iojbl.cn/Article/details/gtemnsmpem.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.havefunace.top/Article/details/gtvfeevvhn.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yuxming.cn/Article/details/gthdwefdli.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jiagoushi.top/Article/details/gtjvdnzexu.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.dianchejie.cn/Article/details/gttdidgogo.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.guannengcc.top/Article/details/gtepjmgomh.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hongshengwenyu.top/Article/details/gtijkchoiy.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.gogol.net.cn/Article/details/gtdcapxxnd.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.kuanghao11.cn/Article/details/gtlusttsqe.html

[B15] 布尔运算与取反
来源：http://dali.zycfv.cn/Article/details/gtxrgpehoe.html

Py:   a and b or not c
来源：http://dali.daxiang520.top/Article/details/gtdukpcokx.html

PHP:  $a && $b || !$c
来源：http://dali.andypj.xyz/Article/details/gtwfttfsjo.html

JS:   a && b || !c
来源：http://dali.316326.xyz/Article/details/gtwxqdyldm.html

TS:   a && b || !c
来源：http://dali.fzhhl.top/Article/details/gtxkwyqeqn.html

Java: a && b || !c
来源：http://dali.316326.xyz/Article/details/gtwdrdiwjr.html

Go:   a && b || !c
来源：http://dali.yonumen.top/Article/details/gtsnvcyodb.html

Ruby: a && b || !c
来源：http://dali.zhaomingkeji.xyz/Article/details/gtihnhgqcm.html

C#:   a && b || !c
来源：http://dali.ppjwa.cn/Article/details/gtzrcogpeu.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.bjfxy.top/Article/details/gtfqwwehnn.html

Py:   if not data: return
来源：http://dali.zycfv.cn/Article/details/gtybahyjjg.html

PHP:  if (!$data) { return; }
来源：http://dali.svipenyu.cn/Article/details/gtdhtnrvwk.html

JS:   if (!data) return;
来源：http://dali.jinqigfzy.top/Article/details/gtkgexilhr.html

TS:   if (!data) return;
来源：http://dali.yuxming.cn/Article/details/gtcoxqgraa.html

Java: if (data == null) return;
来源：http://dali.yuxming.cn/Article/details/gtcqzayiqp.html

Go:   if data == nil { return }
来源：http://dali.smart0.xyz/Article/details/gtjhxcbbpq.html

Ruby: return if data.nil?
来源：http://dali.shzxlz.cn/Article/details/gtadqtcift.html

C#:   if (data == null) return;
来源：http://dali.xziqi.cn/Article/details/gtptcraiks.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsosbosvz.html

C. 函数与作用域
来源：http://dali.hnxiangtu.top/Article/details/gthnttkrvq.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtxefzfqhp.html

[C01] 定义函数
来源：http://dali.xuetiantiany.cn/Article/details/gtnkkpdgdu.html

Py:   def add(a, b): return a + b
来源：http://dali.aibaodan.cn/Article/details/gturpyegvh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ehwqpu.com/Article/details/gtryuthfie.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.vqdsnc.cn/Article/details/gtuqugsatr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.9152youxi.cn/Article/details/gtcszxnbts.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yonumen.top/Article/details/gtpskvaczn.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.chenlongwang.top/Article/details/gtscsuibvb.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhongyouzk.top/Article/details/gtdlkvvijh.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhongyouzk.top/Article/details/gtdgzbouzt.html

[C02] 默认参数
来源：http://dali.redwolf501.top/Article/details/gtpmulxybz.html

Py:   def greet(name="World"): return name
来源：http://dali.xuetiantiany.cn/Article/details/gtyeblytvb.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.bjfxy.top/Article/details/gtgdouzhep.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gttwjvrczm.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.ppjwa.cn/Article/details/gtbrfobsfa.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jinyuanbaomall.cn/Article/details/gtckjulixy.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtqkuauiju.html

Ruby: def greet(name = "World") = name
来源：http://dali.shuidangran.top/Article/details/gtcikxqoqt.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.hywenlv.cn/Article/details/gtwxejqiyc.html

[C03] 可变参数
来源：http://dali.wangshuangyany.cn/Article/details/gtqukprjot.html

Py:   def total(*args): return sum(args)
来源：http://dali.wangshuangyany.cn/Article/details/gtgeeaaojx.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhengqikj.top/Article/details/gteirzflbw.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cqqwz.cn/Article/details/gtcxwyasty.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.quarkkingdee.top/Article/details/gtptygexvf.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.tianlin.xyz/Article/details/gtoyvjmzak.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.xziqi.cn/Article/details/gtljtpinyn.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdovcjlag.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.dashuyun.cn/Article/details/gtkttucmtu.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hnxiangtu.top/Article/details/gtysmqkixs.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.guannengcc.top/Article/details/gtzamlelyd.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtegomvyka.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jqgfzy.top/Article/details/gtysbsmatj.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhoulong.xyz/Article/details/gthndxiqek.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.nanxuanxn.top/Article/details/gtasjvxpku.html

Go:   // 无：用配置结构体参数
来源：http://dali.xuetiantiany.cn/Article/details/gttkxhhsof.html

Ruby: f(a: 1, b: 2)
来源：http://dali.iojbl.cn/Article/details/gtjovoidrg.html

C#:   f(a: 1, b: 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttofjauut.html

[C05] 返回多个值
来源：http://dali.xziqi.cn/Article/details/gtifxpiwfe.html

Py:   return a, b
来源：http://dali.gaohongyu789.top/Article/details/gtfuqjvnyj.html

PHP:  return [$a, $b];
来源：http://dali.gaohongyu789.top/Article/details/gtievhziwv.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.andypj.xyz/Article/details/gtscvoslyy.html

TS:   return { a, b };
来源：http://dali.bjfxy.top/Article/details/gtiieyusou.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jqgufenzy.top/Article/details/gtkcudtlvz.html

Go:   return a, b
来源：http://dali.shanyushiyangtech.top/Article/details/gtazhjdimo.html

Ruby: return a, b
来源：http://dali.iojbl.cn/Article/details/gtkeosccwo.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.shzxlz.cn/Article/details/gtztvulceq.html

[C06] 匿名函数 / lambda
来源：http://dali.hongshengwenyu.top/Article/details/gtmqjisglu.html

Py:   square = lambda x: x * x
来源：http://dali.cheryme.top/Article/details/gtpfmuqoab.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.dianchejie.cn/Article/details/gtjkpdkgjz.html

JS:   const square = x => x * x;
来源：http://dali.sysykeji.top/Article/details/gtxkqrmyyf.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yuxming.cn/Article/details/gtsdjfedrw.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.gaohongyu789.top/Article/details/gtbfzblnxe.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.cdnleiting.top/Article/details/gtwjdzecfe.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yongpay.top/Article/details/gtxrdzyuwk.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.9152youxi.cn/Article/details/gtehsacwzd.html

[C07] 把函数作为参数传入
来源：http://dali.wangshuangyany.cn/Article/details/gtprohyufs.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.ydzc1.top/Article/details/gtwuddtpej.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.redwolf501.top/Article/details/gtolmoxwoq.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.gotoacloud.top/Article/details/gtcaibhavj.html

TS:   arr.map(String)
来源：http://dali.guowangkeji.top/Article/details/gtrrrpuhpt.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.tian-w.cn/Article/details/gtthzmfiec.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.pengpengdd.cyou/Article/details/gtoaskkanv.html

Ruby: arr.map(&:upcase)
来源：http://dali.xuanzx.com/Article/details/gtqkusijko.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yvedp.cn/Article/details/gtjjdzmskc.html

[C08] 闭包
来源：http://dali.hongshengwenyu.top/Article/details/gtiefsbuxv.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.xinyue.icu/Article/details/gtvydpoksp.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yueranfly.top/Article/details/gtexjpdgtg.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yuanzhike.top/Article/details/gtanpzkcie.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yuxming.cn/Article/details/gttcpngkcs.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jqgfzy.top/Article/details/gtlncwmtcn.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.hfpthk.cn/Article/details/gtwmgxadqy.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.guannengcc.top/Article/details/gtmcutwrhw.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.tian-w.cn/Article/details/gtgndqaatz.html

[C09] 递归
来源：http://dali.sysykeji.top/Article/details/gtellwznrz.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hysaishi.cn/Article/details/gtqumoqbkd.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yuanzhike.top/Article/details/gtsszduepk.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsjlbqyas.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xuanzx.com/Article/details/gtvjyghajx.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.andypj.xyz/Article/details/gtihaxnuum.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yj20258.top/Article/details/gtyjckazqg.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yueranfly.top/Article/details/gtkaihmahb.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.guowangkeji.top/Article/details/gtunvezpfa.html

[C10] 变量作用域
来源：http://dali.shanyushiyangtech.top/Article/details/gttlfaxvky.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.quarkkingdee.top/Article/details/gtazeuvjwo.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.c1oappe.top/Article/details/gtxrahaxma.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.nanxinkj.top/Article/details/gtwwbhnkiq.html

TS:   同 JS
来源：http://dali.chenjidiqi.icu/Article/details/gtwnphzbww.html

Java: 方法内为块级作用域
来源：http://dali.xziqi.cn/Article/details/gtgcbcqilr.html

Go:   花括号块级作用域
来源：http://dali.tian-w.cn/Article/details/gtndghecpw.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hnxiangtu.top/Article/details/gthzdnpuaj.html


<!-- 参考信息 -->