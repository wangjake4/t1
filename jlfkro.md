代发 wailian999

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.shzxlz.cn/Article/details/gthxwhrecj.html

Ruby: gets.chomp
来源：http://dali.bjfxy.top/Article/details/gtlujohwhe.html

C#:   Console.ReadLine();
来源：http://dali.meibo888.top/Article/details/gtklpazgbu.html

[A21] 保留指定小数位输出
来源：http://dali.xylfe.cn/Article/details/gtoexxtziy.html

Py:   f"{3.14159:.2f}"
来源：http://dali.jinqigufen.top/Article/details/gtxanhmipq.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.zdqjudy.top/Article/details/gtigxayyxj.html

JS:   (3.14159).toFixed(2)
来源：http://dali.aizwys.cn/Article/details/gtpdovvfhr.html

TS:   (3.14159).toFixed(2)
来源：http://dali.fzhhl.top/Article/details/gtunvkhcdz.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.cucudq.cn/Article/details/gtektvyktz.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.iojbl.cn/Article/details/gtwqtmthka.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.yonumen.top/Article/details/gttggvxkjd.html

C#:   3.14159.ToString("F2")
来源：http://dali.cashguo.top/Article/details/gtklsnnkmu.html

[A22] 获取字符串长度
来源：http://dali.yj20258.top/Article/details/gtgoktvgbj.html

Py:   len(s)
来源：http://dali.aibaodan.cn/Article/details/gtduvrrzjy.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.svipenyu.cn/Article/details/gtzxkalvqb.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.yvedp.cn/Article/details/gtvwpoinnt.html

TS:   s.length
来源：http://dali.havefunace.top/Article/details/gtbpsidjnm.html

Java: s.length()
来源：http://dali.cucudq.cn/Article/details/gtjjpjptcs.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.yonumen.top/Article/details/gttudbevtu.html

Ruby: s.length
来源：http://dali.c1oappe.top/Article/details/gtcrfenfmk.html

C#:   s.Length
来源：http://dali.redwolf501.top/Article/details/gtizagbndz.html

[A23] 大小写转换
来源：http://dali.yueranfly.top/Article/details/gtiaqotsja.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.zhixingplan.top/Article/details/gtbumrdtex.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.pycfn.com/Article/details/gtqogilvtx.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhoulong.xyz/Article/details/gtrautvsxy.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.vqdsnc.cn/Article/details/gtrtaolgsj.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.pycfn.com/Article/details/gtammjabgk.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtldvnpazb.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.shzxlz.cn/Article/details/gtfnixafxs.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.ydzc1.top/Article/details/gtgemwqpry.html

[A24] 去除首尾空白
来源：http://dali.jlsjyb.cn/Article/details/gtunjepghi.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.jianghu66.top/Article/details/gtfrqaefbp.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.jianghu66.top/Article/details/gtqovvbbee.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yuanzhike.top/Article/details/gtftpzsjup.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.chenlongwang.top/Article/details/gtmsolcckv.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.xuanzx.com/Article/details/gtdsvfxybu.html

Go:   strings.TrimSpace(s)
来源：http://dali.aibaodan.cn/Article/details/gtjojntxno.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.sufxvd.cn/Article/details/gtrfonrzyz.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.tianlin.xyz/Article/details/gtummeetzb.html

[A25] 字符串比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gtijfojvxw.html

Py:   s1 == s2; s1 != s2
来源：http://dali.0kj1m.cn/Article/details/gtknpvkibm.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.jyoumei.cn/Article/details/gtzbchzcyk.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.smart0.xyz/Article/details/gtpiivuazd.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.ivvv.top/Article/details/gteovfbzos.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.meibo888.top/Article/details/gtjwpilkzv.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.smart0.xyz/Article/details/gtrxryjbxk.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.aizwys.cn/Article/details/gtrintxjvt.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.hammf.cn/Article/details/gtndwxjmrm.html

[A26] 类型转换总览
来源：http://dali.shanyushiyangkeji.top/Article/details/gtueglvjhz.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.sxryk.cn/Article/details/gttcubdvpt.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.daxiang520.top/Article/details/gttdcsyojx.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.zhixingplan.top/Article/details/gtgndvjfpr.html

TS:   Number() String() Boolean() x as number
来源：http://dali.iojbl.cn/Article/details/gtyrtjurxo.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.pycfn.com/Article/details/gtxfzilblo.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.xziqi.cn/Article/details/gtzvksgyuj.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.xylfe.cn/Article/details/gtvqmzydwd.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.zhongyouzk.top/Article/details/gtstzrwdlx.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtiqlvzxbq.html

B. 流程控制
来源：http://dali.wangshuangyany.cn/Article/details/gtynvuudkx.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtnavppafy.html

[B01] 条件判断 if / else
来源：http://dali.316326.xyz/Article/details/gtrqfsgsch.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.tanke756.top/Article/details/gtkdntyfod.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.xuanzx.com/Article/details/gtczztlroz.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.guowangkeji.top/Article/details/gtocjqyvjb.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jqgufenzy.top/Article/details/gteervqjgd.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.birdmap.top/Article/details/gthkrripyl.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.svipenyu.cn/Article/details/gtqwxexwjw.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.yuanzhike.top/Article/details/gtugceylfm.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.cucudq.cn/Article/details/gtkowmrxwk.html

[B02] 多分支 else if / elif
来源：http://dali.yj20258888.top/Article/details/gtklwyndwp.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.hammf.cn/Article/details/gtkkrqzwvk.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.zhoulong.xyz/Article/details/gtaxuahefv.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhijiandao.cn/Article/details/gtbhrqhfoh.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shuidangran.top/Article/details/gtofsgckof.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ydzc1.top/Article/details/gtjlghhndm.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.yueranfly.top/Article/details/gtyszblhsl.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.yuxming.cn/Article/details/gtryfqcptg.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yueranfly.top/Article/details/gttyyqspix.html

[B03] switch / match / case
来源：http://dali.jqgfzy.top/Article/details/gtjuopartu.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.jiagoushi.top/Article/details/gtpikhbvlu.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.svipenyu.cn/Article/details/gtuvpbzmtf.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.ppjwa.cn/Article/details/gtloljhuua.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.c1oappe.top/Article/details/gtdptcabkl.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.sufxvd.cn/Article/details/gtigebtdce.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.yanxiufei.cn/Article/details/gtsgcqbfpx.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.sysykeji.top/Article/details/gtgplzuvwz.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.yj20258888.top/Article/details/gtjhvggdqq.html

[B04] for 计数循环
来源：http://dali.yvedp.cn/Article/details/gtmlrhssza.html

Py:   for i in range(10): print(i)
来源：http://dali.xuanzx.com/Article/details/gtehdohqwp.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.yueranfly.top/Article/details/gtowdniicz.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.chenjidiqi.icu/Article/details/gtcsaymgoo.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.dashuyun.cn/Article/details/gtbsdhohmy.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.xuanzx.com/Article/details/gtekwzznvz.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.shanyushiyangtech.top/Article/details/gthqjxelht.html

Ruby: 10.times { |i| puts i }
来源：http://dali.cashguo.top/Article/details/gtcthvrhap.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.gaohongyu789.top/Article/details/gtwzywlesw.html

[B05] 遍历数组 / 列表
来源：http://dali.gogol.net.cn/Article/details/gtwyujndcn.html

Py:   for item in arr: print(item)
来源：http://dali.hongshengwenyu.top/Article/details/gtzbnnhmno.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcxkjnsop.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.havefunace.top/Article/details/gtxfvsxizo.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.tian-w.cn/Article/details/gtyfbwbyvv.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.yangfankeji.com/Article/details/gtdpqpqvhg.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.zhengqikj.top/Article/details/gtnvirtzmh.html

Ruby: arr.each { |item| puts item }
来源：http://dali.cheryme.top/Article/details/gtqtxqsvta.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.yueranfly.top/Article/details/gtpvscqbnc.html

[B06] 遍历字典 / 对象
来源：http://dali.pycfn.com/Article/details/gtvsgwzjqu.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.yueranfly.top/Article/details/gtinekumqu.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.andypj.xyz/Article/details/gtlyrwaqfx.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhiwuduotai.top/Article/details/gtkhqxfwkv.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hammf.cn/Article/details/gtvpdkgdga.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.gaohongyu789.top/Article/details/gtwtygtyfg.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.shzxlz.cn/Article/details/gtwmkemgyt.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.jqgfzy.top/Article/details/gtaqhooeza.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.ivvv.top/Article/details/gtgkpmzftl.html

[B07] while 循环
来源：http://dali.haohaochexian.top/Article/details/gtzftvxjbt.html

Py:   while i < 10: i += 1
来源：http://dali.smart0.xyz/Article/details/gtniteupgw.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.ybcxt.top/Article/details/gtxjfqxvrh.html

JS:   while (i < 10) { i++; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtghkddfdv.html

TS:   while (i < 10) { i++; }
来源：http://dali.jqgfzy.top/Article/details/gtggdzybzh.html

Java: while (i < 10) { i++; }
来源：http://dali.guannengcc.top/Article/details/gtsfgwmpup.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.hysaishi.cn/Article/details/gtormwkpbp.html

Ruby: while i < 10; i += 1; end
来源：http://dali.shangyingyoupin.top/Article/details/gthkqfzgis.html

C#:   while (i < 10) { i++; }
来源：http://dali.sufxvd.cn/Article/details/gtgjswbmcn.html

[B08] do-while（至少执行一次）
来源：http://dali.jinqigufen.top/Article/details/gtmwbwxuum.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.jlsjyb.cn/Article/details/gtfzxnllde.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnozpausg.html

JS:   do { i++; } while (i < 10);
来源：http://dali.xylfe.cn/Article/details/gtfgdpigww.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yongpay.top/Article/details/gtdtvnfkln.html

Java: do { i++; } while (i < 10);
来源：http://dali.hysaishi.cn/Article/details/gtdncunvcr.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.daxiang520.top/Article/details/gtzfnnndnz.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yanxiufei.cn/Article/details/gttyihtnlg.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhoulong.xyz/Article/details/gttspucutu.html

[B09] break 与 continue
来源：http://dali.fengsongda.top/Article/details/gthamftlwc.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.tianlin.xyz/Article/details/gtjfsaragv.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.xuetiantiany.cn/Article/details/gtrherbfsd.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhongyouzk.top/Article/details/gtinwqdtxs.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ppjwa.cn/Article/details/gtummozgyz.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenlongwang.top/Article/details/gtsidrebei.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.tian-w.cn/Article/details/gtlshpecdm.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.redwolf501.top/Article/details/gtkkuvhlqy.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hysaishi.cn/Article/details/gtunmzkslk.html

[B10] 遍历同时拿索引
来源：http://dali.aizwys.cn/Article/details/gtoqrqietv.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yanxiufei.cn/Article/details/gtvsabudgs.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.xylfe.cn/Article/details/gteeoqyhne.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.kuanghao11.cn/Article/details/gtvithujyq.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.birdmap.top/Article/details/gtinsnxdlq.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.cdnleiting.top/Article/details/gtpptlosub.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyiuabojw.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.tian-w.cn/Article/details/gtbnbdersm.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhijiandao.cn/Article/details/gtcpjsfrtv.html

[B11] 生成数字序列 / 区间
来源：http://dali.shanyushiyangtech.top/Article/details/gtlhgrypsv.html

Py:   list(range(0, 10, 2))
来源：http://dali.jianghu66.top/Article/details/gtxiarzyaf.html

PHP:  range(0, 10, 2);
来源：http://dali.smart0.xyz/Article/details/gtzjffokso.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.316326.xyz/Article/details/gtmxmreuiz.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yonumen.top/Article/details/gtxmmotlec.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.nanxinkj.top/Article/details/gtyodfoyby.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.cashguo.top/Article/details/gtnkdppput.html

Ruby: (0...10).step(2).to_a
来源：http://dali.wangshuangyany.cn/Article/details/gtepkpkldp.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.cdnleiting.top/Article/details/gtlgnqhkxy.html

[B12] 跳出多层循环
来源：http://dali.jianghu66.top/Article/details/gtmuwyjwkj.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yanxiufei.cn/Article/details/gtfwvcaqme.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.xuanzx.com/Article/details/gtfxabdolh.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.tian-w.cn/Article/details/gtrtvivudo.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.wangdashe.top/Article/details/gtiwjmeday.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenjidiqi.icu/Article/details/gtbrtoouvm.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtqgtubgls.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.xziqi.cn/Article/details/gteeoucvpb.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkzjtvdgi.html

[B13] 判断是否为数字
来源：http://dali.0kj1m.cn/Article/details/gtbalvgzwk.html

Py:   isinstance(x, (int, float))
来源：http://dali.zdqjudy.top/Article/details/gtiuirdcvr.html

PHP:  is_numeric($x)
来源：http://dali.zhoulong.xyz/Article/details/gteylyqtsf.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhiwuduotai.top/Article/details/gthzfextut.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ehwqpu.com/Article/details/gtfvuumasl.html

Java: x instanceof Number
来源：http://dali.hfpthk.cn/Article/details/gteliyssmc.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.aizwys.cn/Article/details/gtjlzcsazb.html

Ruby: x.is_a?(Numeric)
来源：http://dali.xziqi.cn/Article/details/gtxqyicouh.html

C#:   x is int or double or decimal
来源：http://dali.birdmap.top/Article/details/gtmqogmbsp.html

[B14] 判断值是否在集合内
来源：http://dali.jyoumei.cn/Article/details/gtupxzmhwt.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.chenlongwang.top/Article/details/gtlkeklelq.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.xuanzx.com/Article/details/gtfjtmskut.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.shzxlz.cn/Article/details/gtbqpnwllo.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.bjfxy.top/Article/details/gthvqujeeq.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.meibo888.top/Article/details/gtcvnhbrbp.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.fzhhl.top/Article/details/gthzmuxaks.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtlqtkpgan.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtnqkzqkda.html

[B15] 布尔运算与取反
来源：http://dali.shzxlz.cn/Article/details/gtrhyfdtlc.html

Py:   a and b or not c
来源：http://dali.tianlin.xyz/Article/details/gtccwbnmdv.html

PHP:  $a && $b || !$c
来源：http://dali.chenzaomai.com/Article/details/gteybgkqvj.html

JS:   a && b || !c
来源：http://dali.aizwys.cn/Article/details/gtcfstvqze.html

TS:   a && b || !c
来源：http://dali.quarkkingdee.top/Article/details/gtjnuzekem.html

Java: a && b || !c
来源：http://dali.feifeiyinyue.top/Article/details/gtyxmmujhw.html

Go:   a && b || !c
来源：http://dali.hongshengwenyu.top/Article/details/gtonebpvvw.html

Ruby: a && b || !c
来源：http://dali.haohaochexian.top/Article/details/gtqbyqchyw.html

C#:   a && b || !c
来源：http://dali.ywan-chungtsiang.top/Article/details/gttlwgbevc.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.kuanghao11.cn/Article/details/gtmpfaoojh.html

Py:   if not data: return
来源：http://dali.iojbl.cn/Article/details/gtnvszbyyd.html

PHP:  if (!$data) { return; }
来源：http://dali.quarkkingdee.top/Article/details/gtouoxejwr.html

JS:   if (!data) return;
来源：http://dali.jianghu66.top/Article/details/gtawhpnjbb.html

TS:   if (!data) return;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgrbqvmlp.html

Java: if (data == null) return;
来源：http://dali.daria6918.cn/Article/details/gthbtrutad.html

Go:   if data == nil { return }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtztiwvfas.html

Ruby: return if data.nil?
来源：http://dali.redwolf501.top/Article/details/gtzozacoqi.html

C#:   if (data == null) return;
来源：http://dali.shangyingyoupin.top/Article/details/gtjnwvkxgr.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtzljrqmba.html

C. 函数与作用域
来源：http://dali.quarkkingdee.top/Article/details/gtuvqiqsul.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtyuqnvvoo.html

[C01] 定义函数
来源：http://dali.jlsjyb.cn/Article/details/gtxubmeuns.html

Py:   def add(a, b): return a + b
来源：http://dali.xinyue.icu/Article/details/gtdzyieyic.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ppjwa.cn/Article/details/gtwqgfltzy.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.nanxuanxn.top/Article/details/gtbsldzfzf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.0kj1m.cn/Article/details/gtqdrwplvq.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.mhx1999.top/Article/details/gtkhejjusm.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.ydzc1.top/Article/details/gtdglfnglj.html

Ruby: def add(a, b); a + b; end
来源：http://dali.daria6918.cn/Article/details/gtzyalrjij.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.guowangkeji.top/Article/details/gtevcskies.html

[C02] 默认参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwsywcrmk.html

Py:   def greet(name="World"): return name
来源：http://dali.pycfn.com/Article/details/gthutylfng.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.ppjwa.cn/Article/details/gtjrhnzxph.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yj20258.top/Article/details/gtptmwbqws.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jinqigufen.top/Article/details/gtklwbaeps.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yuanzhike.top/Article/details/gtxhdyvfez.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gtsnpdaeaq.html

Ruby: def greet(name = "World") = name
来源：http://dali.hywenlv.cn/Article/details/gtlczulppp.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.tianlin.xyz/Article/details/gtqochgnhv.html

[C03] 可变参数
来源：http://dali.zhengqikj.top/Article/details/gthulhaqwi.html

Py:   def total(*args): return sum(args)
来源：http://dali.mhx1999.top/Article/details/gtezeznaqm.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.0kj1m.cn/Article/details/gtildwiovh.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.0kj1m.cn/Article/details/gtsibuouuz.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.tianlin.xyz/Article/details/gtetjpgfxr.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.aibaodan.cn/Article/details/gtqweivmpr.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.tianlin.xyz/Article/details/gtnfuytyqc.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.iojbl.cn/Article/details/gtsjtnkuox.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.ydzc1.top/Article/details/gtdrjegzvc.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hywenlv.cn/Article/details/gtdivgsjnp.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.hywenlv.cn/Article/details/gtxjustjgq.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jqgfzy.top/Article/details/gtklwloais.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yonumen.top/Article/details/gtcemsvnuy.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.ppjwa.cn/Article/details/gtrzpxbhos.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xylfe.cn/Article/details/gtzqkesiwv.html

Go:   // 无：用配置结构体参数
来源：http://dali.jinqigufen.top/Article/details/gtuvclvwmm.html

Ruby: f(a: 1, b: 2)
来源：http://dali.shuidangran.top/Article/details/gtxqueylvr.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhengqikj.top/Article/details/gtmllklmbi.html

[C05] 返回多个值
来源：http://dali.guowangkeji.top/Article/details/gtmxkcoqga.html

Py:   return a, b
来源：http://dali.tanke756.top/Article/details/gttmdxuxyy.html

PHP:  return [$a, $b];
来源：http://dali.cheryme.top/Article/details/gtqkbdarvy.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.hfpthk.cn/Article/details/gtgqaqumjq.html

TS:   return { a, b };
来源：http://dali.gzhubu.top/Article/details/gteadmezne.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.quarkkingdee.top/Article/details/gtcstavpxr.html

Go:   return a, b
来源：http://dali.xinyue.icu/Article/details/gtzmhxawlw.html

Ruby: return a, b
来源：http://dali.jlsjyb.cn/Article/details/gtwkbqrvxk.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhengqikj.top/Article/details/gttwmuwadd.html

[C06] 匿名函数 / lambda
来源：http://dali.jinqigufen.top/Article/details/gtwxfkmbdj.html

Py:   square = lambda x: x * x
来源：http://dali.jqgufenzy.top/Article/details/gtnfmbwlph.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.guannengcc.top/Article/details/gtsbsjvibp.html

JS:   const square = x => x * x;
来源：http://dali.ivvv.top/Article/details/gtxhjsnsrs.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlizxuqcp.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.hongshengwenyu.top/Article/details/gtgajmnjhc.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hysaishi.cn/Article/details/gtqyqanbcp.html

Ruby: square = ->(x) { x * x }
来源：http://dali.dashuyun.cn/Article/details/gtkdsbtmgs.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.gogol.net.cn/Article/details/gthgqjtcox.html

[C07] 把函数作为参数传入
来源：http://dali.gogol.net.cn/Article/details/gthqticcmd.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jqgfzy.top/Article/details/gtctznamfs.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yj20258.top/Article/details/gthhexmcvj.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.nanxinkj.top/Article/details/gtgaocmzpx.html

TS:   arr.map(String)
来源：http://dali.mhx1999.top/Article/details/gtikiwzyub.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.cashguo.top/Article/details/gtpqdmatlp.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.cashguo.top/Article/details/gtetusinom.html

Ruby: arr.map(&:upcase)
来源：http://dali.sxryk.cn/Article/details/gthmdldpgq.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.ppjwa.cn/Article/details/gtimknbyun.html

[C08] 闭包
来源：http://dali.jyoumei.cn/Article/details/gtwlnxrxeh.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.nanxinkj.top/Article/details/gttppuqcwp.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.wangdashe.top/Article/details/gtfhzefwcc.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.xuetiantiany.cn/Article/details/gtlcoprcms.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gthbxxknwx.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.shanyushiyangkeji.top/Article/details/gtopsdrtmt.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhiwuduotai.top/Article/details/gtoowabgvd.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.cheryme.top/Article/details/gtkqjswlgt.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.daxiang520.top/Article/details/gtyvueatyb.html

[C09] 递归
来源：http://dali.hysaishi.cn/Article/details/gtenfzeltv.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvshfifwk.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.smart0.xyz/Article/details/gtidhbkglj.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.nanxuanxn.top/Article/details/gtbghyqnzp.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.redwolf501.top/Article/details/gtbmhbnqig.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yvedp.cn/Article/details/gtlmpxkyxr.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yonumen.top/Article/details/gtcerbfaim.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.andypj.xyz/Article/details/gtlwgcwrvo.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.meibo888.top/Article/details/gteokjactr.html

[C10] 变量作用域
来源：http://dali.jlsjyb.cn/Article/details/gtlctgzqap.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.haohaochexian.top/Article/details/gtzxvepqhg.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.nwbrower.top/Article/details/gttzvpyroa.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.chenjidiqi.icu/Article/details/gtqbzbxrmd.html

TS:   同 JS
来源：http://dali.0kj1m.cn/Article/details/gtjrbigycl.html

Java: 方法内为块级作用域
来源：http://dali.fzhhl.top/Article/details/gttrhqrkwt.html

Go:   花括号块级作用域
来源：http://dali.tanke756.top/Article/details/gtrmcdojog.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.tianlin.xyz/Article/details/gttdgfnohh.html

C#:   块级作用域
来源：http://dali.guowangkeji.top/Article/details/gtpzwgxhlo.html

[C11] 模块导入与导出
来源：http://dali.cucudq.cn/Article/details/gtwwtljmqg.html

Py:   from module import func
来源：http://dali.sufxvd.cn/Article/details/gtewcbfpto.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yonumen.top/Article/details/gtvqwxfiaq.html


<!-- 参考信息 -->