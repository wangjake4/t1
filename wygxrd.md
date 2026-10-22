代发 wailian999

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.fzhhl.top/Article/details/gt2acptzhwm.html

Ruby: gets.chomp
来源：http://dali.tian-w.cn/Article/details/gt2mwqjyxjo.html

C#:   Console.ReadLine();
来源：http://dali.zhongyouzk.top/Article/details/gt2jfapfxua.html

[A21] 保留指定小数位输出
来源：http://dali.xuetiantiany.cn/Article/details/gt2lrrkogeo.html

Py:   f"{3.14159:.2f}"
来源：http://dali.ppjwa.cn/Article/details/gt2jrfotdwb.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.yj202588.top/Article/details/gt2fxqxhlmr.html

JS:   (3.14159).toFixed(2)
来源：http://dali.yuxming.cn/Article/details/gt2hsyirrxu.html

TS:   (3.14159).toFixed(2)
来源：http://dali.jlsjyb.cn/Article/details/gt2bpbjleto.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.gzhubu.top/Article/details/gt2xocynkjf.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.gogol.net.cn/Article/details/gt2zwxtghbk.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.snrcjt.cn/Article/details/gt2xlvbkfdu.html

C#:   3.14159.ToString("F2")
来源：http://dali.xylfe.cn/Article/details/gt2xixqjpml.html

[A22] 获取字符串长度
来源：http://dali.xinyue.icu/Article/details/gt2owcfgejf.html

Py:   len(s)
来源：http://dali.yuxming.cn/Article/details/gt2ougrnmuo.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.jyoumei.cn/Article/details/gt2vcewhwhn.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xaouqfvu.html

TS:   s.length
来源：http://dali.yangfankeji.com/Article/details/gt2krgqrvyz.html

Java: s.length()
来源：http://dali.jiagoushi.top/Article/details/gt2tskbhqab.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.bjfxy.top/Article/details/gt2mdlouzve.html

Ruby: s.length
来源：http://dali.yj20258888.top/Article/details/gt2hhxgldgt.html

C#:   s.Length
来源：http://dali.tanke756.top/Article/details/gt2prmvvpqo.html

[A23] 大小写转换
来源：http://dali.zhixingplan.top/Article/details/gt2qymagywq.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.shzxlz.cn/Article/details/gt2whtmlxcq.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.bjfxy.top/Article/details/gt2hobnzwzg.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.ppjwa.cn/Article/details/gt2dklgxcdj.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jyoumei.cn/Article/details/gt2eexmbbbt.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.xziqi.cn/Article/details/gt2aehsqncp.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2mamcrnrg.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.gzhubu.top/Article/details/gt2bckdzuaf.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.yuxming.cn/Article/details/gt2ngoecvko.html

[A24] 去除首尾空白
来源：http://dali.c1oappe.top/Article/details/gt2mdhuyypy.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.hfpthk.cn/Article/details/gt2fsadzclb.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.yangfankeji.com/Article/details/gt2otysudck.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.chenlongwang.top/Article/details/gt2kzvouebe.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.smart0.xyz/Article/details/gt2nfmjuyih.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.dashuyun.cn/Article/details/gt2ibjbzxzu.html

Go:   strings.TrimSpace(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ifosoqai.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.ydzc1.top/Article/details/gt2gqhwlkwn.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.wangshuangyany.cn/Article/details/gt2hhcjyfog.html

[A25] 字符串比较
来源：http://dali.hywenlv.cn/Article/details/gt2wikozlps.html

Py:   s1 == s2; s1 != s2
来源：http://dali.havefunace.top/Article/details/gt2hmfxwwho.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.yueranfly.top/Article/details/gt2hrmzzbbl.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.xuanzx.com/Article/details/gt2wxvkgdqx.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.bjfxy.top/Article/details/gt2ghsqszay.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.zdqjudy.top/Article/details/gt2onmdyhww.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.tianlin.xyz/Article/details/gt2hairkvpo.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.chenzaomai.com/Article/details/gt2cmdweedw.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.svipenyu.cn/Article/details/gt2azbyhpxs.html

[A26] 类型转换总览
来源：http://dali.svipenyu.cn/Article/details/gt2ooultwaj.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.yuanzhike.top/Article/details/gt2gcohnrla.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.gotoacloud.top/Article/details/gt2cngfxiin.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.hongshengwenyu.top/Article/details/gt2wtigpvby.html

TS:   Number() String() Boolean() x as number
来源：http://dali.kuanghao11.cn/Article/details/gt2jjbgchui.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.cdnleiting.top/Article/details/gt2qwcuvpeo.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.quarkkingdee.top/Article/details/gt2zinmgatr.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pyfgqbof.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.yuanzhike.top/Article/details/gt2bsdyfmoz.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2rmibbquw.html

B. 流程控制
来源：http://dali.tianlin.xyz/Article/details/gt2gcdwjtah.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2lntwgftk.html

[B01] 条件判断 if / else
来源：http://dali.shangyingyoupin.top/Article/details/gt2pyhjunxx.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.xuetiantiany.cn/Article/details/gt2gxktjzsi.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.ybcxt.top/Article/details/gt2gbnvskxg.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.shuidangran.top/Article/details/gt2uooafvrn.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hysaishi.cn/Article/details/gt2owjjnagj.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.birdmap.top/Article/details/gt2knygqxst.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.andypj.xyz/Article/details/gt2iljfsnwt.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.sufxvd.cn/Article/details/gt2jxcklved.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.birdmap.top/Article/details/gt2mcnougfl.html

[B02] 多分支 else if / elif
来源：http://dali.jianghu66.top/Article/details/gt2lpyjpzef.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kjihofpk.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.jqgfzy.top/Article/details/gt2tewnyiop.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hfpthk.cn/Article/details/gt2igakmcmz.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.tianlin.xyz/Article/details/gt2levfrhml.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yueranfly.top/Article/details/gt2ixfmgvvu.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.haohaochexian.top/Article/details/gt2iqrsaody.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.aizwys.cn/Article/details/gt2gmkawfhz.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.9152youxi.cn/Article/details/gt2cqfxpykk.html

[B03] switch / match / case
来源：http://dali.kuanghao11.cn/Article/details/gt2hijzqfjs.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.daria6918.cn/Article/details/gt2kqopmozf.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.zycfv.cn/Article/details/gt2fxsczdcj.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hlewyqzs.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.kuanghao11.cn/Article/details/gt2rtwtxiyi.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.gogol.net.cn/Article/details/gt2mezxyacc.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.xuanzx.com/Article/details/gt2mrvsdjaj.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.iojbl.cn/Article/details/gt2sxahhwsa.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.guowangkeji.top/Article/details/gt2gmqvfxhi.html

[B04] for 计数循环
来源：http://dali.pycfn.com/Article/details/gt2ueofcfms.html

Py:   for i in range(10): print(i)
来源：http://dali.gogol.net.cn/Article/details/gt2zyhyjwnh.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.zhengqikj.top/Article/details/gt2mfotlifa.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2auhybxmg.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nuikmjxe.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.cdnleiting.top/Article/details/gt2aeydzepj.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.feifeiyinyue.top/Article/details/gt2wgwiewxb.html

Ruby: 10.times { |i| puts i }
来源：http://dali.jqgfzy.top/Article/details/gt2jtufegjf.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikvxzhey.html

[B05] 遍历数组 / 列表
来源：http://dali.shuidangran.top/Article/details/gt2rgoknlqw.html

Py:   for item in arr: print(item)
来源：http://dali.cashguo.top/Article/details/gt2wdlqapyl.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.gogol.net.cn/Article/details/gt2wvwjdlxx.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.sxryk.cn/Article/details/gt2impyhndy.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2hemjvmsq.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.havefunace.top/Article/details/gt2lttsrgmk.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.cheryme.top/Article/details/gt2ysqjlplt.html

Ruby: arr.each { |item| puts item }
来源：http://dali.bjfxy.top/Article/details/gt2ifmfkpbh.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.tianlin.xyz/Article/details/gt2qmtwemai.html

[B06] 遍历字典 / 对象
来源：http://dali.jinqigufen.top/Article/details/gt2wycxwrii.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.nanxinkj.top/Article/details/gt2yrnplwzt.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.hnqzz.top/Article/details/gt2tidoniin.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yangfankeji.com/Article/details/gt2mxvrcyxx.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.daria6918.cn/Article/details/gt2yrzbxfvx.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.haohaochexian.top/Article/details/gt2afzekqhq.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.c1oappe.top/Article/details/gt2qqgixrdo.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.ivvv.top/Article/details/gt2ssvuvbqk.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.iojbl.cn/Article/details/gt2alselpjo.html

[B07] while 循环
来源：http://dali.guowangkeji.top/Article/details/gt2yvxsprby.html

Py:   while i < 10: i += 1
来源：http://dali.daria6918.cn/Article/details/gt2ynkwfpvq.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.aibaodan.cn/Article/details/gt2vrvmbnas.html

JS:   while (i < 10) { i++; }
来源：http://dali.xuanzx.com/Article/details/gt2jkdjieit.html

TS:   while (i < 10) { i++; }
来源：http://dali.ppjwa.cn/Article/details/gt2wxndespw.html

Java: while (i < 10) { i++; }
来源：http://dali.aizwys.cn/Article/details/gt2tiybyigq.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.jlsjyb.cn/Article/details/gt2ksqidfif.html

Ruby: while i < 10; i += 1; end
来源：http://dali.daxiang520.top/Article/details/gt2pllguhsh.html

C#:   while (i < 10) { i++; }
来源：http://dali.yuxming.cn/Article/details/gt2gdwxgnvd.html

[B08] do-while（至少执行一次）
来源：http://dali.svipenyu.cn/Article/details/gt2zfsnnhse.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.hammf.cn/Article/details/gt2mwvrlorh.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.ivvv.top/Article/details/gt2bxppepxb.html

JS:   do { i++; } while (i < 10);
来源：http://dali.xuanzx.com/Article/details/gt2zugacoim.html

TS:   do { i++; } while (i < 10);
来源：http://dali.sysykeji.top/Article/details/gt2aeinvsqq.html

Java: do { i++; } while (i < 10);
来源：http://dali.dianchejie.cn/Article/details/gt2sqwkllte.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.sufxvd.cn/Article/details/gt2vvpokbnm.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.chenzaomai.com/Article/details/gt2bhccayzk.html

C#:   do { i++; } while (i < 10);
来源：http://dali.nanxinkj.top/Article/details/gt2bjnqoscx.html

[B09] break 与 continue
来源：http://dali.guowangkeji.top/Article/details/gt2aoirizrc.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.hfpthk.cn/Article/details/gt2bmxyxpue.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yj20258.top/Article/details/gt2bjppbdrq.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ehwqpu.com/Article/details/gt2zremvcxn.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.snrcjt.cn/Article/details/gt2lztsdkxk.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhixingplan.top/Article/details/gt2rkdrbkly.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zycfv.cn/Article/details/gt2ysnlpadm.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.chenjidiqi.icu/Article/details/gt2lfekqtql.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhengqikj.top/Article/details/gt2wununhcl.html

[B10] 遍历同时拿索引
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qcphhers.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.aizwys.cn/Article/details/gt2ikydvjsf.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.kuanghao11.cn/Article/details/gt2gxlolbah.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xbtjoxtw.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.daria6918.cn/Article/details/gt2mjiwswql.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vcuqhwkf.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.tian-w.cn/Article/details/gt2xgzccrzh.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2inxlsmma.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jianghu66.top/Article/details/gt2bwtxobrj.html

[B11] 生成数字序列 / 区间
来源：http://dali.zycfv.cn/Article/details/gt2bmmdnksf.html

Py:   list(range(0, 10, 2))
来源：http://dali.wangdashe.top/Article/details/gt2pvbnktgk.html

PHP:  range(0, 10, 2);
来源：http://dali.ydzc1.top/Article/details/gt2mvoqgegd.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.fzhhl.top/Article/details/gt2xubwrpll.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.fengsongda.top/Article/details/gt2fgidcpmi.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yvedp.cn/Article/details/gt2iagsyklr.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yj20258.top/Article/details/gt2gwvkafrr.html

Ruby: (0...10).step(2).to_a
来源：http://dali.fengsongda.top/Article/details/gt2bzyrgfsi.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.iojbl.cn/Article/details/gt2jtqnekgw.html

[B12] 跳出多层循环
来源：http://dali.fengsongda.top/Article/details/gt2wuoshuby.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.vqdsnc.cn/Article/details/gt2ovqrnqri.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.smart0.xyz/Article/details/gt2vwzokasb.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yanxiufei.cn/Article/details/gt2bjsifmok.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenjidiqi.icu/Article/details/gt2zcjhtdzl.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.snrcjt.cn/Article/details/gt2dfjhhrlx.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yj202588.top/Article/details/gt2yrekcsgq.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.birdmap.top/Article/details/gt2plsnfbop.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.xinyue.icu/Article/details/gt2qhhukaoc.html

[B13] 判断是否为数字
来源：http://dali.gaohongyu789.top/Article/details/gt2ydewoosd.html

Py:   isinstance(x, (int, float))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qpwvcnxk.html

PHP:  is_numeric($x)
来源：http://dali.jinqigfzy.top/Article/details/gt2wxdrgfbz.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.gotoacloud.top/Article/details/gt2bgrxenkn.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.daxiang520.top/Article/details/gt2whppskzy.html

Java: x instanceof Number
来源：http://dali.yongpay.top/Article/details/gt2swknsvnx.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.wangshuangyany.cn/Article/details/gt2yzequlfo.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2omynwgfc.html

C#:   x is int or double or decimal
来源：http://dali.nanxuanxn.top/Article/details/gt2zsvnvjuq.html

[B14] 判断值是否在集合内
来源：http://dali.wangshuangyany.cn/Article/details/gt2cwugbfbl.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yj202588.top/Article/details/gt2efgtqwwv.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yvedp.cn/Article/details/gt2tergrmgv.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.shzxlz.cn/Article/details/gt2thvqixfm.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.sxryk.cn/Article/details/gt2dqkpmnhb.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.tanke756.top/Article/details/gt2zumudoto.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yj20258.top/Article/details/gt2whrrzlck.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.wangdashe.top/Article/details/gt2dcrahilb.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhengqikj.top/Article/details/gt2xmvckawg.html

[B15] 布尔运算与取反
来源：http://dali.tianlin.xyz/Article/details/gt2kwlxxzhb.html

Py:   a and b or not c
来源：http://dali.meibo888.top/Article/details/gt2qmwqfwet.html

PHP:  $a && $b || !$c
来源：http://dali.tian-w.cn/Article/details/gt2pgunyhta.html

JS:   a && b || !c
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nutdqhlr.html

TS:   a && b || !c
来源：http://dali.sysykeji.top/Article/details/gt2hthafavs.html

Java: a && b || !c
来源：http://dali.sweek.top/Article/details/gt2hljlgeiq.html

Go:   a && b || !c
来源：http://dali.yuxming.cn/Article/details/gt2hjehwzkt.html

Ruby: a && b || !c
来源：http://dali.chenjidiqi.icu/Article/details/gt2umdjxhuk.html

C#:   a && b || !c
来源：http://dali.xinyue.icu/Article/details/gt2fadsiaol.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.aizwys.cn/Article/details/gt2ebiqolpr.html

Py:   if not data: return
来源：http://dali.yj20258.top/Article/details/gt2ihhofqxv.html

PHP:  if (!$data) { return; }
来源：http://dali.yueranfly.top/Article/details/gt2jegrtrsb.html

JS:   if (!data) return;
来源：http://dali.meibo888.top/Article/details/gt2frxzxjrp.html

TS:   if (!data) return;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kuuzmymi.html

Java: if (data == null) return;
来源：http://dali.xinyue.icu/Article/details/gt2xvogslpt.html

Go:   if data == nil { return }
来源：http://dali.sysykeji.top/Article/details/gt2perguvtv.html

Ruby: return if data.nil?
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2folwqhtz.html

C#:   if (data == null) return;
来源：http://dali.hywenlv.cn/Article/details/gt2nwjbfyjz.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2zijkaudb.html

C. 函数与作用域
来源：http://dali.guowangkeji.top/Article/details/gt2hrtmlvxb.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2aogjwxmz.html

[C01] 定义函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xrquxton.html

Py:   def add(a, b): return a + b
来源：http://dali.sweek.top/Article/details/gt2ccoplqei.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.daxiang520.top/Article/details/gt2ecotfhvm.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.fzhhl.top/Article/details/gt2sgdvdcmw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ekltwtrr.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.sweek.top/Article/details/gt2flvdxrst.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.ybcxt.top/Article/details/gt2lppnhspf.html

Ruby: def add(a, b); a + b; end
来源：http://dali.snrcjt.cn/Article/details/gt2pxudjtvs.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hammf.cn/Article/details/gt2govfsjbo.html

[C02] 默认参数
来源：http://dali.jqgfzy.top/Article/details/gt2tzhlkzwc.html

Py:   def greet(name="World"): return name
来源：http://dali.hongshengwenyu.top/Article/details/gt2oonvgzib.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yvedp.cn/Article/details/gt2ldtezuhr.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2izjtevxs.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.xinyue.icu/Article/details/gt2pondxecp.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yvedp.cn/Article/details/gt2smsijmfg.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.vqdsnc.cn/Article/details/gt2oturdpmw.html

Ruby: def greet(name = "World") = name
来源：http://dali.ivvv.top/Article/details/gt2bhzgocfy.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.guowangkeji.top/Article/details/gt2hjwznnka.html

[C03] 可变参数
来源：http://dali.tian-w.cn/Article/details/gt2mgikfbcr.html

Py:   def total(*args): return sum(args)
来源：http://dali.nanxinkj.top/Article/details/gt2dtnukmvp.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yonumen.top/Article/details/gt2vbvbqhxb.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.0kj1m.cn/Article/details/gt2cwfdbmef.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj20258888.top/Article/details/gt2bcqugzag.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.xziqi.cn/Article/details/gt2duqgptnh.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.feifeiyinyue.top/Article/details/gt2yvtnqldv.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yjiduecx.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.hongshengwenyu.top/Article/details/gt2cunavbmr.html

[C04] 命名参数 / 关键字参数
来源：http://dali.gotoacloud.top/Article/details/gt2ocsxrlkr.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.andypj.xyz/Article/details/gt2uvggddoe.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xinyue.icu/Article/details/gt2qrugyxed.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2txkiwbuk.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.pengpengdd.cyou/Article/details/gt2vptiejkn.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xziqi.cn/Article/details/gt2ggbnpgzi.html

Go:   // 无：用配置结构体参数
来源：http://dali.ybcxt.top/Article/details/gt2iahclgpd.html

Ruby: f(a: 1, b: 2)
来源：http://dali.cashguo.top/Article/details/gt2lhybtvay.html

C#:   f(a: 1, b: 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fgrstxzy.html

[C05] 返回多个值
来源：http://dali.ehwqpu.com/Article/details/gt2vnbezagu.html

Py:   return a, b
来源：http://dali.hysaishi.cn/Article/details/gt2xxxpgybz.html

PHP:  return [$a, $b];
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ikwaqkoj.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.sweek.top/Article/details/gt2bxgzuquh.html

TS:   return { a, b };
来源：http://dali.hnqzz.top/Article/details/gt2reritbic.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.xinyue.icu/Article/details/gt2yeczrvuw.html

Go:   return a, b
来源：http://dali.zhengqikj.top/Article/details/gt2jscrodpi.html

Ruby: return a, b
来源：http://dali.andypj.xyz/Article/details/gt2suytkluz.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.ppjwa.cn/Article/details/gt2asobubtn.html

[C06] 匿名函数 / lambda
来源：http://dali.sysykeji.top/Article/details/gt2qvhjegrt.html

Py:   square = lambda x: x * x
来源：http://dali.jianghu66.top/Article/details/gt2hmcgavaz.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.fzhhl.top/Article/details/gt2laszqvsv.html

JS:   const square = x => x * x;
来源：http://dali.wangdashe.top/Article/details/gt2lhpfbzcm.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.snrcjt.cn/Article/details/gt2kizywqkp.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.snrcjt.cn/Article/details/gt2xqbodady.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.haohaochexian.top/Article/details/gt2xgofjnfx.html

Ruby: square = ->(x) { x * x }
来源：http://dali.ppjwa.cn/Article/details/gt2mxpcsllz.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.dianchejie.cn/Article/details/gt2wawkzryd.html

[C07] 把函数作为参数传入
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kjzzmeps.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hywenlv.cn/Article/details/gt2ugrootfz.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.fzhhl.top/Article/details/gt2saijjxtw.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.quarkkingdee.top/Article/details/gt2miujoyqp.html

TS:   arr.map(String)
来源：http://dali.chenlongwang.top/Article/details/gt2tzbmotva.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.feifeiyinyue.top/Article/details/gt2dlupenif.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.sufxvd.cn/Article/details/gt2vkdrplee.html

Ruby: arr.map(&:upcase)
来源：http://dali.aizwys.cn/Article/details/gt2vduyozsc.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.cqqwz.cn/Article/details/gt2ubozspem.html

[C08] 闭包
来源：http://dali.jinqigfzy.top/Article/details/gt2ponpkqpi.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.fengsongda.top/Article/details/gt2tiaogtrb.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hammf.cn/Article/details/gt2jhrvixtz.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.havefunace.top/Article/details/gt2ilanyozv.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uccwjsst.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yanxiufei.cn/Article/details/gt2ixkimrrx.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.sweek.top/Article/details/gt2ebqofgsw.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.tian-w.cn/Article/details/gt2rjfdgpfj.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.tianlin.xyz/Article/details/gt2ibrdlnkp.html

[C09] 递归
来源：http://dali.gzhubu.top/Article/details/gt2gauyltfw.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.svipenyu.cn/Article/details/gt2iroimshz.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.hfpthk.cn/Article/details/gt2figucpzj.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj202588.top/Article/details/gt2cqcoodbb.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinqigufen.top/Article/details/gt2gnwecuuq.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.dianchejie.cn/Article/details/gt2oubgdrwb.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zdqjudy.top/Article/details/gt2uwnpkkja.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jinqigfzy.top/Article/details/gt2hlykohdh.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.sufxvd.cn/Article/details/gt2yaudlgsm.html

[C10] 变量作用域
来源：http://dali.9152youxi.cn/Article/details/gt2letyyptr.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.meibo888.top/Article/details/gt2oirkhinf.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhiwuduotai.top/Article/details/gt2uugfponc.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zdqjudy.top/Article/details/gt2mztquunp.html

TS:   同 JS
来源：http://dali.yongpay.top/Article/details/gt2umfncrfh.html

Java: 方法内为块级作用域
来源：http://dali.wangshuangyany.cn/Article/details/gt2qzwgouhc.html

Go:   花括号块级作用域
来源：http://dali.chenzaomai.com/Article/details/gt2ynennjxo.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.sweek.top/Article/details/gt2vqrxrnjl.html

C#:   块级作用域
来源：http://dali.yangfankeji.com/Article/details/gt2otiqboxx.html

[C11] 模块导入与导出
来源：http://dali.haohaochexian.top/Article/details/gt2zygxcvgi.html

Py:   from module import func
来源：http://dali.gzhubu.top/Article/details/gt2xecdobqp.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhixingplan.top/Article/details/gt2mngtkaoj.html


<!-- 参考信息 -->