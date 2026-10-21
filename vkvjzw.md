代发 wailian999

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.xziqi.cn/Article/details/gttavgulye.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.zhoulong.xyz/Article/details/gtsfzecflu.html

TS:   // Node.js：readline 模块
来源：http://dali.0kj1m.cn/Article/details/gtqqsephmo.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.yangfankeji.com/Article/details/gtejucyswq.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.9152youxi.cn/Article/details/gtamcpvygm.html

Ruby: gets.chomp
来源：http://dali.chenlongwang.top/Article/details/gtgnqwubru.html

C#:   Console.ReadLine();
来源：http://dali.yvedp.cn/Article/details/gtxshayrhe.html

[A21] 保留指定小数位输出
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjyeuetwy.html

Py:   f"{3.14159:.2f}"
来源：http://dali.mhx1999.top/Article/details/gtewlvnvxe.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.aibaodan.cn/Article/details/gtvrctxpnv.html

JS:   (3.14159).toFixed(2)
来源：http://dali.wangshuangyany.cn/Article/details/gtugsgyial.html

TS:   (3.14159).toFixed(2)
来源：http://dali.shzxlz.cn/Article/details/gtxxxmsnrx.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.nanxuanxn.top/Article/details/gtepnpsdcv.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.redwolf501.top/Article/details/gtlrmmdsvr.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.fzhhl.top/Article/details/gtvezxtjjy.html

C#:   3.14159.ToString("F2")
来源：http://dali.yj20258.top/Article/details/gttrdbstnh.html

[A22] 获取字符串长度
来源：http://dali.chenlongwang.top/Article/details/gtgfnyohkj.html

Py:   len(s)
来源：http://dali.daxiang520.top/Article/details/gtqtckrohm.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.yuxming.cn/Article/details/gtmvasdpaw.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.mhx1999.top/Article/details/gtmzhileru.html

TS:   s.length
来源：http://dali.xylfe.cn/Article/details/gtdngvqeil.html

Java: s.length()
来源：http://dali.yvedp.cn/Article/details/gtsdvvevyl.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtufkrwsrv.html

Ruby: s.length
来源：http://dali.haohaochexian.top/Article/details/gtwglgiohr.html

C#:   s.Length
来源：http://dali.guowangkeji.top/Article/details/gtcrzzypsh.html

[A23] 大小写转换
来源：http://dali.chenjidiqi.icu/Article/details/gtzoadlycb.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.0kj1m.cn/Article/details/gtjcqipvqe.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.yueranfly.top/Article/details/gtyogulxfk.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jlsjyb.cn/Article/details/gtakynrtrg.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jyoumei.cn/Article/details/gtevwxdovi.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.vqdsnc.cn/Article/details/gthyiowlsx.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.smart0.xyz/Article/details/gtsrllcfph.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.jinqigufen.top/Article/details/gtqvvnlnbn.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.andypj.xyz/Article/details/gtwjpolzcb.html

[A24] 去除首尾空白
来源：http://dali.zhixingplan.top/Article/details/gttiqsnqym.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.9152youxi.cn/Article/details/gtjqljecfu.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.ppjwa.cn/Article/details/gtbodgtkwu.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.tanke756.top/Article/details/gtxvatxwhm.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.cashguo.top/Article/details/gtvxphgpmh.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.tanke756.top/Article/details/gthzheeopx.html

Go:   strings.TrimSpace(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtjgkqiyik.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.hnqzz.top/Article/details/gtrdhymkla.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.vqdsnc.cn/Article/details/gtejthmfhn.html

[A25] 字符串比较
来源：http://dali.sysykeji.top/Article/details/gtcrjrwufe.html

Py:   s1 == s2; s1 != s2
来源：http://dali.sysykeji.top/Article/details/gtxnumhzfw.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.jinqigufen.top/Article/details/gtnomlhnkg.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.xuanzx.com/Article/details/gtozozdmgg.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhixingplan.top/Article/details/gtpegluzli.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.kuanghao11.cn/Article/details/gtjhbunimn.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtobmbwqsd.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.tian-w.cn/Article/details/gtrqtmhmql.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.nwbrower.top/Article/details/gtbalysdan.html

[A26] 类型转换总览
来源：http://dali.kuanghao11.cn/Article/details/gtgwbtpjde.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.sufxvd.cn/Article/details/gtaobhvyyn.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.yongpay.top/Article/details/gtxksdfvqv.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtabbopztl.html

TS:   Number() String() Boolean() x as number
来源：http://dali.pengpengdd.cyou/Article/details/gtczuoflrw.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.yanxiufei.cn/Article/details/gtezmwrmrb.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.bjfxy.top/Article/details/gtptiiqmra.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.cdnleiting.top/Article/details/gtutiyfbgj.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.ivvv.top/Article/details/gtmsudtdsa.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtrnwcpilm.html

B. 流程控制
来源：http://dali.iojbl.cn/Article/details/gtjqvbtioo.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtdkdilvvh.html

[B01] 条件判断 if / else
来源：http://dali.mhx1999.top/Article/details/gteqwvzfzt.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.nanxinkj.top/Article/details/gtxaqwghrc.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.yj20258.top/Article/details/gtgoerkplx.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yj20258888.top/Article/details/gtbhbzhefw.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.xziqi.cn/Article/details/gtlrgymafw.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.xuanzx.com/Article/details/gtwxewfvmp.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.cucudq.cn/Article/details/gtndhwkkph.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.dianchejie.cn/Article/details/gtxodgrwyd.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.xuanzx.com/Article/details/gtshmshauo.html

[B02] 多分支 else if / elif
来源：http://dali.gotoacloud.top/Article/details/gtwieyhlpe.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbxlnggkf.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.c1oappe.top/Article/details/gtmxtesotl.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhongyouzk.top/Article/details/gtbublxajr.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hfpthk.cn/Article/details/gtpcfotyoo.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hnxiangtu.top/Article/details/gtowfxgdiv.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.xuanzx.com/Article/details/gtiqnjkkka.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.tianlin.xyz/Article/details/gtxfffjblx.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.nwbrower.top/Article/details/gtbryzbvcx.html

[B03] switch / match / case
来源：http://dali.fengsongda.top/Article/details/gtsyxjhysj.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.sweek.top/Article/details/gtrsdaklit.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.tianlin.xyz/Article/details/gtvmidfdqd.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.hnqzz.top/Article/details/gtsscqwuee.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yj20258.top/Article/details/gttyrkkroc.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.zhoulong.xyz/Article/details/gtijrkqjop.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.sweek.top/Article/details/gtjsouxslj.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.sweek.top/Article/details/gtaalbbcvw.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.tianlin.xyz/Article/details/gtgbvnqovp.html

[B04] for 计数循环
来源：http://dali.iojbl.cn/Article/details/gtvbavdrvw.html

Py:   for i in range(10): print(i)
来源：http://dali.guowangkeji.top/Article/details/gtvechvczo.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.jiagoushi.top/Article/details/gtsmgqwbxr.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.nanxuanxn.top/Article/details/gtiegpordq.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.smart0.xyz/Article/details/gtskmqgcbn.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.gotoacloud.top/Article/details/gtdwcnndgq.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.nanxuanxn.top/Article/details/gtmyhtfmjc.html

Ruby: 10.times { |i| puts i }
来源：http://dali.cheryme.top/Article/details/gtxgjjqgzn.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.xylfe.cn/Article/details/gtjttljyvx.html

[B05] 遍历数组 / 列表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkblvtdrn.html

Py:   for item in arr: print(item)
来源：http://dali.jlsjyb.cn/Article/details/gthkhmeeaf.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.wangshuangyany.cn/Article/details/gtmrhmbubz.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.jqgufenzy.top/Article/details/gtupmyoyio.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.daria6918.cn/Article/details/gtwgreyfmq.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.tanke756.top/Article/details/gtxvxygfzl.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.gotoacloud.top/Article/details/gthbumrytl.html

Ruby: arr.each { |item| puts item }
来源：http://dali.shangyingyoupin.top/Article/details/gtggzlmfyw.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.wangdashe.top/Article/details/gtwbnucirp.html

[B06] 遍历字典 / 对象
来源：http://dali.wangdashe.top/Article/details/gtpciamzua.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.hongshengwenyu.top/Article/details/gtehjoctmr.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.chenzaomai.com/Article/details/gtsmzkradd.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqqpsqpqo.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.havefunace.top/Article/details/gtzxhzfxaw.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.hfpthk.cn/Article/details/gtqcefpmbv.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.snrcjt.cn/Article/details/gtxqwljbnk.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.hnqzz.top/Article/details/gtadrbaoyq.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yvedp.cn/Article/details/gtsyrcdemy.html

[B07] while 循环
来源：http://dali.hywenlv.cn/Article/details/gtykiqxptr.html

Py:   while i < 10: i += 1
来源：http://dali.pycfn.com/Article/details/gtgpqaspdh.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtawfmrvzs.html

JS:   while (i < 10) { i++; }
来源：http://dali.iojbl.cn/Article/details/gtmoyxtina.html

TS:   while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gtuujncyes.html

Java: while (i < 10) { i++; }
来源：http://dali.sxryk.cn/Article/details/gtkqyjmdcb.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.shanyushiyangtech.top/Article/details/gtmfodttfo.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zhengqikj.top/Article/details/gtmqgcsloz.html

C#:   while (i < 10) { i++; }
来源：http://dali.sweek.top/Article/details/gtaqggjtoo.html

[B08] do-while（至少执行一次）
来源：http://dali.hnqzz.top/Article/details/gtaoaufhin.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yuxming.cn/Article/details/gttmgtfzwj.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.shzxlz.cn/Article/details/gtlmdlytnf.html

JS:   do { i++; } while (i < 10);
来源：http://dali.jinqigufen.top/Article/details/gtjqbxcbhv.html

TS:   do { i++; } while (i < 10);
来源：http://dali.tian-w.cn/Article/details/gthpqwwsbp.html

Java: do { i++; } while (i < 10);
来源：http://dali.nanxinkj.top/Article/details/gtzidfsrnh.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtprwvvqmj.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.tanke756.top/Article/details/gtmsyuszhd.html

C#:   do { i++; } while (i < 10);
来源：http://dali.aibaodan.cn/Article/details/gtawzfpzwe.html

[B09] break 与 continue
来源：http://dali.kuanghao11.cn/Article/details/gtxhivleqq.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.jlsjyb.cn/Article/details/gtqxjzozpj.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.daria6918.cn/Article/details/gttrynevso.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sufxvd.cn/Article/details/gtfyvgwpbp.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhiwuduotai.top/Article/details/gtlgqyhdbf.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.fzhhl.top/Article/details/gtokkpzvek.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jinqigfzy.top/Article/details/gtosbflmka.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.jiagoushi.top/Article/details/gtwskwhtto.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtclkspacf.html

[B10] 遍历同时拿索引
来源：http://dali.aibaodan.cn/Article/details/gtjvgujmcd.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.sxryk.cn/Article/details/gtpwlfmofl.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhoulong.xyz/Article/details/gtiznypaet.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.kuanghao11.cn/Article/details/gtlfvfyese.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhoulong.xyz/Article/details/gtqwlcgihs.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.dashuyun.cn/Article/details/gtuykjhojh.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.0kj1m.cn/Article/details/gtcdipwaai.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.cdnleiting.top/Article/details/gtcbedatpw.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.hysaishi.cn/Article/details/gtwgekogio.html

[B11] 生成数字序列 / 区间
来源：http://dali.dashuyun.cn/Article/details/gtuqcmdbuu.html

Py:   list(range(0, 10, 2))
来源：http://dali.daxiang520.top/Article/details/gtboaeiybm.html

PHP:  range(0, 10, 2);
来源：http://dali.kuanghao11.cn/Article/details/gtlwfjxuzg.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hywenlv.cn/Article/details/gtfdjgnjim.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hnxiangtu.top/Article/details/gtseeevpfd.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.svipenyu.cn/Article/details/gtibpyfldw.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.cdnleiting.top/Article/details/gtwmjxusqq.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhiwuduotai.top/Article/details/gtnhfsmqqd.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.0kj1m.cn/Article/details/gtprgoeeoj.html

[B12] 跳出多层循环
来源：http://dali.feifeiyinyue.top/Article/details/gtafpklkgm.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.aibaodan.cn/Article/details/gtlnrbqyfd.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.meibo888.top/Article/details/gtkqngddyd.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.gzhubu.top/Article/details/gtgwldyrwb.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xuanzx.com/Article/details/gtnhhccxgr.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhongyouzk.top/Article/details/gtnjxuknei.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yj20258888.top/Article/details/gtzgjkzbuj.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yueranfly.top/Article/details/gtsfsrmxnf.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.dashuyun.cn/Article/details/gtafniyyjt.html

[B13] 判断是否为数字
来源：http://dali.zhiwuduotai.top/Article/details/gtrwchrvke.html

Py:   isinstance(x, (int, float))
来源：http://dali.wangshuangyany.cn/Article/details/gtirmpfxqc.html

PHP:  is_numeric($x)
来源：http://dali.hfpthk.cn/Article/details/gtuoenojzl.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.9152youxi.cn/Article/details/gtwesniuvd.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwnzrktyp.html

Java: x instanceof Number
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrevrench.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zdqjudy.top/Article/details/gtckxaqcam.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhongyouzk.top/Article/details/gtuqlofecv.html

C#:   x is int or double or decimal
来源：http://dali.zhiwuduotai.top/Article/details/gtshuuxztp.html

[B14] 判断值是否在集合内
来源：http://dali.chenlongwang.top/Article/details/gtpxpinuiy.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.pengpengdd.cyou/Article/details/gtmtglgekl.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtntgronrj.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.cqqwz.cn/Article/details/gtpzjegazw.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.bjfxy.top/Article/details/gtpyzuuyml.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jiagoushi.top/Article/details/gtmqujpyve.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hywenlv.cn/Article/details/gtmyiuuniq.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.cashguo.top/Article/details/gtpyqmywqv.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.vqdsnc.cn/Article/details/gtswmnxhjz.html

[B15] 布尔运算与取反
来源：http://dali.cqqwz.cn/Article/details/gtksugqaqp.html

Py:   a and b or not c
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjogjvjji.html

PHP:  $a && $b || !$c
来源：http://dali.birdmap.top/Article/details/gtvoeqziel.html

JS:   a && b || !c
来源：http://dali.quarkkingdee.top/Article/details/gtptavlkoq.html

TS:   a && b || !c
来源：http://dali.ywan-chungtsiang.top/Article/details/gtajuvkhfe.html

Java: a && b || !c
来源：http://dali.cashguo.top/Article/details/gtrugycyng.html

Go:   a && b || !c
来源：http://dali.cqqwz.cn/Article/details/gtpqdqavol.html

Ruby: a && b || !c
来源：http://dali.gotoacloud.top/Article/details/gttfdaohol.html

C#:   a && b || !c
来源：http://dali.zhaomingkeji.xyz/Article/details/gttcglbhye.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.cheryme.top/Article/details/gtyuyavgwy.html

Py:   if not data: return
来源：http://dali.yvedp.cn/Article/details/gtxrwciwaa.html

PHP:  if (!$data) { return; }
来源：http://dali.0kj1m.cn/Article/details/gtomgyvdgh.html

JS:   if (!data) return;
来源：http://dali.cdnleiting.top/Article/details/gtjyustmfx.html

TS:   if (!data) return;
来源：http://dali.shuidangran.top/Article/details/gtdnztfnkf.html

Java: if (data == null) return;
来源：http://dali.jqgfzy.top/Article/details/gtdbcofisf.html

Go:   if data == nil { return }
来源：http://dali.meibo888.top/Article/details/gtbngpuiis.html

Ruby: return if data.nil?
来源：http://dali.0kj1m.cn/Article/details/gtkjkwrpgj.html

C#:   if (data == null) return;
来源：http://dali.zhoulong.xyz/Article/details/gtqbfwxvzw.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtfmvizsct.html

C. 函数与作用域
来源：http://dali.yonumen.top/Article/details/gtjclrideh.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gteeiwsogr.html

[C01] 定义函数
来源：http://dali.guowangkeji.top/Article/details/gtuffxwnik.html

Py:   def add(a, b): return a + b
来源：http://dali.jqgufenzy.top/Article/details/gtsqcyoraa.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.redwolf501.top/Article/details/gtflhgoeic.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.chenzaomai.com/Article/details/gtqhbfckji.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gtjjdvkipx.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.havefunace.top/Article/details/gtlyacdtwm.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yonumen.top/Article/details/gtplfpakyt.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xinyue.icu/Article/details/gtbxsigwyc.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.svipenyu.cn/Article/details/gtndyvfqof.html

[C02] 默认参数
来源：http://dali.guowangkeji.top/Article/details/gtpupglsft.html

Py:   def greet(name="World"): return name
来源：http://dali.gzhubu.top/Article/details/gtjnsvcwyq.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.nanxuanxn.top/Article/details/gtphhvznox.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yueranfly.top/Article/details/gtxxisbadc.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.ybcxt.top/Article/details/gtnvntekne.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.tanke756.top/Article/details/gtxmzusaog.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hywenlv.cn/Article/details/gtxbshlmjt.html

Ruby: def greet(name = "World") = name
来源：http://dali.jlsjyb.cn/Article/details/gtbbnwhokk.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jlsjyb.cn/Article/details/gtlacqrgve.html

[C03] 可变参数
来源：http://dali.cheryme.top/Article/details/gtznwihflc.html

Py:   def total(*args): return sum(args)
来源：http://dali.yonumen.top/Article/details/gtuealeiia.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.chenlongwang.top/Article/details/gtqtdtkval.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.fzhhl.top/Article/details/gtbcrwjjwq.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.tian-w.cn/Article/details/gtytwohxcs.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.guowangkeji.top/Article/details/gtpjpclrhq.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jinqigufen.top/Article/details/gtxdwmbvld.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.snrcjt.cn/Article/details/gtadaallyr.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jinqigfzy.top/Article/details/gtkifacssy.html

[C04] 命名参数 / 关键字参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdtubybtp.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yj20258.top/Article/details/gtnqefuufu.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jqgfzy.top/Article/details/gtobmmhkna.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hnqzz.top/Article/details/gtgqtedawg.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.xuetiantiany.cn/Article/details/gtjnojseue.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.shangyingyoupin.top/Article/details/gtvfhaoaml.html

Go:   // 无：用配置结构体参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtukvncjsg.html

Ruby: f(a: 1, b: 2)
来源：http://dali.bjfxy.top/Article/details/gtitmskrnm.html

C#:   f(a: 1, b: 2)
来源：http://dali.guannengcc.top/Article/details/gtmnqrsdch.html

[C05] 返回多个值
来源：http://dali.cucudq.cn/Article/details/gtnajpwzsg.html

Py:   return a, b
来源：http://dali.yj20258.top/Article/details/gtrybxowry.html

PHP:  return [$a, $b];
来源：http://dali.ehwqpu.com/Article/details/gtysqfekxi.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.tianlin.xyz/Article/details/gtjtvzwelh.html

TS:   return { a, b };
来源：http://dali.xinyue.icu/Article/details/gtgftlzawz.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jianghu66.top/Article/details/gtbgbzrmtl.html

Go:   return a, b
来源：http://dali.shangyingyoupin.top/Article/details/gtmryhthll.html

Ruby: return a, b
来源：http://dali.shanyushiyangtech.top/Article/details/gtilpeqyop.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhengqikj.top/Article/details/gtcyucspxn.html

[C06] 匿名函数 / lambda
来源：http://dali.gaohongyu789.top/Article/details/gtkmnfptsn.html

Py:   square = lambda x: x * x
来源：http://dali.hongshengwenyu.top/Article/details/gtroyuggsy.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hongshengwenyu.top/Article/details/gtdkojdyfe.html

JS:   const square = x => x * x;
来源：http://dali.ehwqpu.com/Article/details/gthkmbouxb.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yj20258888.top/Article/details/gttknjdkud.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.hnxiangtu.top/Article/details/gtxgqfttvk.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jinqigfzy.top/Article/details/gtyszblpae.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yangfankeji.com/Article/details/gtchmlrifz.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yuxming.cn/Article/details/gtnletvahi.html

[C07] 把函数作为参数传入
来源：http://dali.vqdsnc.cn/Article/details/gtklccjinc.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hongshengwenyu.top/Article/details/gtdwsoomje.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.nanxuanxn.top/Article/details/gtdpkodncw.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.cdnleiting.top/Article/details/gtayvgiaqk.html

TS:   arr.map(String)
来源：http://dali.wangdashe.top/Article/details/gtuglopxrv.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtgqryhtrg.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.guowangkeji.top/Article/details/gthodusetu.html

Ruby: arr.map(&:upcase)
来源：http://dali.zdqjudy.top/Article/details/gttmhnqnpn.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.ydzc1.top/Article/details/gtvanqjhsu.html

[C08] 闭包
来源：http://dali.jqgufenzy.top/Article/details/gtmyhvcxom.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.nwbrower.top/Article/details/gtiwjzhtci.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gtbfadlzdu.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.xuanzx.com/Article/details/gtxeenotzl.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.cheryme.top/Article/details/gtktxlyxtp.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yongpay.top/Article/details/gtueqtahlc.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.nanxinkj.top/Article/details/gttclbcgzq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hnxiangtu.top/Article/details/gttsgskfxv.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yongpay.top/Article/details/gtwnrafjhj.html

[C09] 递归
来源：http://dali.yj20258888.top/Article/details/gtuuwrqujj.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yanxiufei.cn/Article/details/gtzfaavlgl.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.ehwqpu.com/Article/details/gttanwaiml.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jqgufenzy.top/Article/details/gtekxxbngo.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.quarkkingdee.top/Article/details/gtvhcthbgk.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yangfankeji.com/Article/details/gtrriaucjx.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hnqzz.top/Article/details/gtmppyxtxp.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.gotoacloud.top/Article/details/gtwanndyko.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.pengpengdd.cyou/Article/details/gtdzfsriml.html

[C10] 变量作用域
来源：http://dali.mhx1999.top/Article/details/gtnrhkdunk.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.bjfxy.top/Article/details/gtkvnkfvvd.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzzynyrvq.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.guannengcc.top/Article/details/gtpxfsygtj.html

TS:   同 JS
来源：http://dali.wangdashe.top/Article/details/gtcipercvp.html

Java: 方法内为块级作用域
来源：http://dali.cucudq.cn/Article/details/gtfmsarrlj.html

Go:   花括号块级作用域
来源：http://dali.hfpthk.cn/Article/details/gtabcyftuz.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.gogol.net.cn/Article/details/gtcontowcz.html


<!-- 参考信息 -->