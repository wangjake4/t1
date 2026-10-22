代发 wailian999

Java: String.format("%.2f", 3.14159)
来源：http://dali.ehwqpu.com/Article/details/gt2avwoawrw.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.dashuyun.cn/Article/details/gt2qpfpipqh.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.dashuyun.cn/Article/details/gt2revlfuwp.html

C#:   3.14159.ToString("F2")
来源：http://dali.dianchejie.cn/Article/details/gt2jowokwqx.html

[A22] 获取字符串长度
来源：http://dali.vqdsnc.cn/Article/details/gt2mccszdcy.html

Py:   len(s)
来源：http://dali.andypj.xyz/Article/details/gt2bmcerzyw.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2emlxaedt.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.jqgufenzy.top/Article/details/gt2kvtmnggx.html

TS:   s.length
来源：http://dali.ppjwa.cn/Article/details/gt2tvoxuzng.html

Java: s.length()
来源：http://dali.yangfankeji.com/Article/details/gt2uhklnbmc.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.zhixingplan.top/Article/details/gt2vbjwuelm.html

Ruby: s.length
来源：http://dali.zhengqikj.top/Article/details/gt2uildaofl.html

C#:   s.Length
来源：http://dali.zhengqikj.top/Article/details/gt2onlvsrcm.html

[A23] 大小写转换
来源：http://dali.yvedp.cn/Article/details/gt2bnisxfmn.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.chenzaomai.com/Article/details/gt2rhiqwswc.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.cdnleiting.top/Article/details/gt2rhapopcd.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.pengpengdd.cyou/Article/details/gt2jnqvmdfu.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.xinyue.icu/Article/details/gt2ppezched.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhongyouzk.top/Article/details/gt2hzxmtivj.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2psbdqxst.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.meibo888.top/Article/details/gt2rgxrrqxj.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.cucudq.cn/Article/details/gt2humpzjqm.html

[A24] 去除首尾空白
来源：http://dali.zhixingplan.top/Article/details/gt2ujyimjoc.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.ppjwa.cn/Article/details/gt2gqhmhkuu.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.nanxuanxn.top/Article/details/gt2vgfrmned.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cyteuobk.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.hammf.cn/Article/details/gt2woqqmxua.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.yuxming.cn/Article/details/gt2brtuokul.html

Go:   strings.TrimSpace(s)
来源：http://dali.zhixingplan.top/Article/details/gt2cbfwrkpl.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.feifeiyinyue.top/Article/details/gt2ledhynlk.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.xylfe.cn/Article/details/gt2stvpwons.html

[A25] 字符串比较
来源：http://dali.gogol.net.cn/Article/details/gt2tiarrugl.html

Py:   s1 == s2; s1 != s2
来源：http://dali.andypj.xyz/Article/details/gt2bifzusxe.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.jinqigfzy.top/Article/details/gt2yetlkxjt.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxzegbpd.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jqgufenzy.top/Article/details/gt2fxtiblwz.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.zdqjudy.top/Article/details/gt2dvonlxwo.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.jinqigufen.top/Article/details/gt2eiuicfaw.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.shangyingyoupin.top/Article/details/gt2tthpugoq.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.xylfe.cn/Article/details/gt2ruqmyjcu.html

[A26] 类型转换总览
来源：http://dali.gaohongyu789.top/Article/details/gt2xqgmteru.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.jinqigfzy.top/Article/details/gt2mrejjdpk.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.svipenyu.cn/Article/details/gt2pnyzbzbc.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.cashguo.top/Article/details/gt2rluqoakd.html

TS:   Number() String() Boolean() x as number
来源：http://dali.zhijiandao.cn/Article/details/gt2mnmzqgsn.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.hammf.cn/Article/details/gt2rgqvzfus.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.yanxiufei.cn/Article/details/gt2lvvrsuqa.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.zhengqikj.top/Article/details/gt2gryaexlh.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.chenjidiqi.icu/Article/details/gt2fowiuabu.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2iziwywpw.html

B. 流程控制
来源：http://dali.yuanzhike.top/Article/details/gt2ptrmxkwk.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2yqyzbwes.html

[B01] 条件判断 if / else
来源：http://dali.gzhubu.top/Article/details/gt2lytmcfvq.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.aibaodan.cn/Article/details/gt2ebhhyixw.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.nanxinkj.top/Article/details/gt2tkmxlkpv.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hywenlv.cn/Article/details/gt2wfjjvcst.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.cashguo.top/Article/details/gt2uvbnalld.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.nwbrower.top/Article/details/gt2qaquzofu.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.redwolf501.top/Article/details/gt2clzfdxub.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.zhijiandao.cn/Article/details/gt2eqopwpsi.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.shangyingyoupin.top/Article/details/gt2fokxuljq.html

[B02] 多分支 else if / elif
来源：http://dali.yanxiufei.cn/Article/details/gt2nrfngvfh.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.smart0.xyz/Article/details/gt2kgapkjma.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.yj20258888.top/Article/details/gt2ehbxylvr.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shanyushiyangtech.top/Article/details/gt2migxnrkg.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sufxvd.cn/Article/details/gt2jebenoho.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.aibaodan.cn/Article/details/gt2zayiwanh.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.zhoulong.xyz/Article/details/gt2lycxhrzg.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nubahikd.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.aizwys.cn/Article/details/gt2yscdxtlw.html

[B03] switch / match / case
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tyuhygsk.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.ybcxt.top/Article/details/gt2jxkmjoxr.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.nanxinkj.top/Article/details/gt2mnvwzrme.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jiagoushi.top/Article/details/gt2cqcvmika.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.cashguo.top/Article/details/gt2jlfjeprp.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2twarlkhr.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.hysaishi.cn/Article/details/gt2bhfsbnrq.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.gaohongyu789.top/Article/details/gt2okmukoht.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.hywenlv.cn/Article/details/gt2mbvtubhs.html

[B04] for 计数循环
来源：http://dali.jinqigfzy.top/Article/details/gt2xrecnndk.html

Py:   for i in range(10): print(i)
来源：http://dali.shuidangran.top/Article/details/gt2cedgzgfq.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.sysykeji.top/Article/details/gt2bvtlbuyt.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.sweek.top/Article/details/gt2rbtxuaka.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yongpay.top/Article/details/gt2hruifanf.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.gaohongyu789.top/Article/details/gt2sgezbhnb.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.c1oappe.top/Article/details/gt2ivwnlmri.html

Ruby: 10.times { |i| puts i }
来源：http://dali.mhx1999.top/Article/details/gt2spzuuhkv.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ykpicurr.html

[B05] 遍历数组 / 列表
来源：http://dali.cucudq.cn/Article/details/gt2ngwiqkmx.html

Py:   for item in arr: print(item)
来源：http://dali.chenjidiqi.icu/Article/details/gt2hjaasimf.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.jqgfzy.top/Article/details/gt2wegsgcou.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.shuidangran.top/Article/details/gt2vlgnhpvr.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.iojbl.cn/Article/details/gt2jgiplgzv.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.tian-w.cn/Article/details/gt2cobxlafp.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.dianchejie.cn/Article/details/gt2zdqimumn.html

Ruby: arr.each { |item| puts item }
来源：http://dali.dashuyun.cn/Article/details/gt2qbjgqczh.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.yuanzhike.top/Article/details/gt2frovbhec.html

[B06] 遍历字典 / 对象
来源：http://dali.feifeiyinyue.top/Article/details/gt2yygbfmje.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.yongpay.top/Article/details/gt2hmyqapwk.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.hywenlv.cn/Article/details/gt2lljfxycr.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2uncdjpdh.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.tanke756.top/Article/details/gt2qrwxujej.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.c1oappe.top/Article/details/gt2uvtuuygw.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.dashuyun.cn/Article/details/gt2nxqgphtb.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.kuanghao11.cn/Article/details/gt2ugkibtql.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.smart0.xyz/Article/details/gt2mlisrviy.html

[B07] while 循环
来源：http://dali.sysykeji.top/Article/details/gt2kskhkwmm.html

Py:   while i < 10: i += 1
来源：http://dali.yj20258.top/Article/details/gt2lovpukgl.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.bjfxy.top/Article/details/gt2pueomekp.html

JS:   while (i < 10) { i++; }
来源：http://dali.gotoacloud.top/Article/details/gt2wtanwusy.html

TS:   while (i < 10) { i++; }
来源：http://dali.vqdsnc.cn/Article/details/gt2zzwllykw.html

Java: while (i < 10) { i++; }
来源：http://dali.aibaodan.cn/Article/details/gt2kxlxhlbi.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.jyoumei.cn/Article/details/gt2sqzswhyj.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zhongyouzk.top/Article/details/gt2ilkhwuan.html

C#:   while (i < 10) { i++; }
来源：http://dali.sysykeji.top/Article/details/gt2zejwszjx.html

[B08] do-while（至少执行一次）
来源：http://dali.meibo888.top/Article/details/gt2hfulxmpc.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.feifeiyinyue.top/Article/details/gt2hzgmzbjm.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.c1oappe.top/Article/details/gt2soztdhyf.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhongyouzk.top/Article/details/gt2fobdbckt.html

TS:   do { i++; } while (i < 10);
来源：http://dali.shzxlz.cn/Article/details/gt2yylckqlw.html

Java: do { i++; } while (i < 10);
来源：http://dali.aizwys.cn/Article/details/gt2xndsdtqr.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.0kj1m.cn/Article/details/gt2vetnhcgl.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.wangshuangyany.cn/Article/details/gt2ztunabdi.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yongpay.top/Article/details/gt2cscdjcwl.html

[B09] break 与 continue
来源：http://dali.iojbl.cn/Article/details/gt2edakvrtv.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.ehwqpu.com/Article/details/gt2ejzmjsrb.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.tanke756.top/Article/details/gt2swlelaug.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gogol.net.cn/Article/details/gt2evnqtaxv.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kxvpmnkc.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj202588.top/Article/details/gt2thgqghhp.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.meibo888.top/Article/details/gt2ixzvhwun.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.vqdsnc.cn/Article/details/gt2vznngwvp.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.fengsongda.top/Article/details/gt2zqrrewnm.html

[B10] 遍历同时拿索引
来源：http://dali.xziqi.cn/Article/details/gt2zphdijor.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.haohaochexian.top/Article/details/gt2lvfitrmi.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hrpenfox.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.hnxiangtu.top/Article/details/gt2cygrrabl.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.tanke756.top/Article/details/gt2rwbnbzuq.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.cdnleiting.top/Article/details/gt2rbnziodo.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.ehwqpu.com/Article/details/gt2lgfklzzt.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hywenlv.cn/Article/details/gt2ksnytjrb.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.hfpthk.cn/Article/details/gt2tmzieovw.html

[B11] 生成数字序列 / 区间
来源：http://dali.tanke756.top/Article/details/gt2hrhtidcq.html

Py:   list(range(0, 10, 2))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mpaqzyxh.html

PHP:  range(0, 10, 2);
来源：http://dali.svipenyu.cn/Article/details/gt2vktgweru.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2dydrydeu.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jyoumei.cn/Article/details/gt2igllodrf.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qkretmkq.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jiagoushi.top/Article/details/gt2mgqrmxku.html

Ruby: (0...10).step(2).to_a
来源：http://dali.sufxvd.cn/Article/details/gt2wwxijcvo.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.chenjidiqi.icu/Article/details/gt2rkwttroj.html

[B12] 跳出多层循环
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ghxdngzj.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.xuanzx.com/Article/details/gt2gqxapegg.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.gogol.net.cn/Article/details/gt2vlclfunk.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2brkgmjhj.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.vqdsnc.cn/Article/details/gt2xdlbpjpp.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.cheryme.top/Article/details/gt2siutvhce.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhiwuduotai.top/Article/details/gt2rxusnjci.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yj20258888.top/Article/details/gt2okckqnzt.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bpxkzvsp.html

[B13] 判断是否为数字
来源：http://dali.cucudq.cn/Article/details/gt2kklwbdqk.html

Py:   isinstance(x, (int, float))
来源：http://dali.wangdashe.top/Article/details/gt2cggtwkku.html

PHP:  is_numeric($x)
来源：http://dali.zdqjudy.top/Article/details/gt2avdmrfkl.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yj20258.top/Article/details/gt2tnmcnlxw.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.tanke756.top/Article/details/gt2faoxwszv.html

Java: x instanceof Number
来源：http://dali.xylfe.cn/Article/details/gt2vwotoxsz.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gueknkyi.html

Ruby: x.is_a?(Numeric)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ujbmwvzn.html

C#:   x is int or double or decimal
来源：http://dali.yuxming.cn/Article/details/gt2xwkrgvkr.html

[B14] 判断值是否在集合内
来源：http://dali.nwbrower.top/Article/details/gt2mdexjslr.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.cucudq.cn/Article/details/gt2ukuagfiu.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.ivvv.top/Article/details/gt2wijguvki.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.ydzc1.top/Article/details/gt2pmzcbzwj.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.mhx1999.top/Article/details/gt2mcbdnbem.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.fengsongda.top/Article/details/gt2scrvugdx.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.sxryk.cn/Article/details/gt2ibfdhoee.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.sysykeji.top/Article/details/gt2xvkdqrjs.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.sysykeji.top/Article/details/gt2xdhadbnq.html

[B15] 布尔运算与取反
来源：http://dali.jiagoushi.top/Article/details/gt2svlvkdon.html

Py:   a and b or not c
来源：http://dali.haohaochexian.top/Article/details/gt2pdieizpe.html

PHP:  $a && $b || !$c
来源：http://dali.nanxuanxn.top/Article/details/gt2wmmgaghf.html

JS:   a && b || !c
来源：http://dali.wangshuangyany.cn/Article/details/gt2qhzddpqy.html

TS:   a && b || !c
来源：http://dali.sweek.top/Article/details/gt2xfdyqpoz.html

Java: a && b || !c
来源：http://dali.sysykeji.top/Article/details/gt2twiqajgp.html

Go:   a && b || !c
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lyshdedj.html

Ruby: a && b || !c
来源：http://dali.yuanzhike.top/Article/details/gt2xbjjkdqk.html

C#:   a && b || !c
来源：http://dali.fengsongda.top/Article/details/gt2zeavgnxw.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.havefunace.top/Article/details/gt2pfoaaacg.html

Py:   if not data: return
来源：http://dali.ivvv.top/Article/details/gt2pwpcbknj.html

PHP:  if (!$data) { return; }
来源：http://dali.yj20258888.top/Article/details/gt2fsmeesxu.html

JS:   if (!data) return;
来源：http://dali.hnqzz.top/Article/details/gt2clnxetuy.html

TS:   if (!data) return;
来源：http://dali.xziqi.cn/Article/details/gt2xfgxxplr.html

Java: if (data == null) return;
来源：http://dali.hfpthk.cn/Article/details/gt2ezykaknu.html

Go:   if data == nil { return }
来源：http://dali.chenzaomai.com/Article/details/gt2vuzqcqin.html

Ruby: return if data.nil?
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wxacxmyy.html

C#:   if (data == null) return;
来源：http://dali.tanke756.top/Article/details/gt2azpimijt.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2odbxqnyl.html

C. 函数与作用域
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ojktfrnn.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2dsizcblu.html

[C01] 定义函数
来源：http://dali.chenjidiqi.icu/Article/details/gt2fccyapvn.html

Py:   def add(a, b): return a + b
来源：http://dali.vqdsnc.cn/Article/details/gt2vkofsdye.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cashguo.top/Article/details/gt2bzyytizl.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yuxming.cn/Article/details/gt2gpdqqyao.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.bjfxy.top/Article/details/gt2kdqoiigz.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yvedp.cn/Article/details/gt2hoiqmfww.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.aizwys.cn/Article/details/gt2sxrjokjl.html

Ruby: def add(a, b); a + b; end
来源：http://dali.pycfn.com/Article/details/gt2efejtfil.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zycfv.cn/Article/details/gt2ohnkaxbw.html

[C02] 默认参数
来源：http://dali.iojbl.cn/Article/details/gt2zfhibeby.html

Py:   def greet(name="World"): return name
来源：http://dali.sxryk.cn/Article/details/gt2nkocmtpv.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.cashguo.top/Article/details/gt2qcgpvxpy.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hammf.cn/Article/details/gt2fsknvnlt.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.fzhhl.top/Article/details/gt2xzjwscgn.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jmmvdjgt.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.pengpengdd.cyou/Article/details/gt2hwymfobo.html

Ruby: def greet(name = "World") = name
来源：http://dali.tian-w.cn/Article/details/gt2ivzsqfxh.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.ehwqpu.com/Article/details/gt2nqgdzwsc.html

[C03] 可变参数
来源：http://dali.tanke756.top/Article/details/gt2bwioutgi.html

Py:   def total(*args): return sum(args)
来源：http://dali.316326.xyz/Article/details/gt2nnynmisg.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.gogol.net.cn/Article/details/gt2sqgatgby.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yonumen.top/Article/details/gt2ifzcyvzm.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cqqwz.cn/Article/details/gt2hiukoyhx.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.fzhhl.top/Article/details/gt2hxgnjlsw.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kgcfckba.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.sufxvd.cn/Article/details/gt2idndkuyn.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.svipenyu.cn/Article/details/gt2niiyymau.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zdqjudy.top/Article/details/gt2xclmsbqb.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ibfdqafd.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.daria6918.cn/Article/details/gt2cfqrtgmq.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.cucudq.cn/Article/details/gt2jfzrhwkw.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.snrcjt.cn/Article/details/gt2ewhspeys.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.cheryme.top/Article/details/gt2medafvmd.html

Go:   // 无：用配置结构体参数
来源：http://dali.ivvv.top/Article/details/gt2digbacaq.html

Ruby: f(a: 1, b: 2)
来源：http://dali.fzhhl.top/Article/details/gt2hganbxnv.html

C#:   f(a: 1, b: 2)
来源：http://dali.yvedp.cn/Article/details/gt2wrjviaio.html

[C05] 返回多个值
来源：http://dali.xziqi.cn/Article/details/gt2yqjaruyk.html

Py:   return a, b
来源：http://dali.bjfxy.top/Article/details/gt2nkkcrkcb.html

PHP:  return [$a, $b];
来源：http://dali.0kj1m.cn/Article/details/gt2iyuybcmu.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.chenzaomai.com/Article/details/gt2ddicahfq.html

TS:   return { a, b };
来源：http://dali.chenzaomai.com/Article/details/gt2faxfhpvi.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yonumen.top/Article/details/gt2keckjcbj.html

Go:   return a, b
来源：http://dali.cucudq.cn/Article/details/gt2olxhqhyz.html

Ruby: return a, b
来源：http://dali.guannengcc.top/Article/details/gt2zmzmtjcx.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.aizwys.cn/Article/details/gt2hllqgdgy.html

[C06] 匿名函数 / lambda
来源：http://dali.ehwqpu.com/Article/details/gt2idaacwnr.html

Py:   square = lambda x: x * x
来源：http://dali.0kj1m.cn/Article/details/gt2snrjhfru.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.svipenyu.cn/Article/details/gt2rywtwuzh.html

JS:   const square = x => x * x;
来源：http://dali.shzxlz.cn/Article/details/gt2xdawaoqk.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jinqigufen.top/Article/details/gt2qfqgetbl.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.pengpengdd.cyou/Article/details/gt2abekdtim.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.chenlongwang.top/Article/details/gt2dukequrt.html

Ruby: square = ->(x) { x * x }
来源：http://dali.tianlin.xyz/Article/details/gt2zlzhrskf.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.cashguo.top/Article/details/gt2cdimwmvc.html

[C07] 把函数作为参数传入
来源：http://dali.zhixingplan.top/Article/details/gt2ecxdoppf.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hongshengwenyu.top/Article/details/gt2qnqjfjwm.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2okzaoscu.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xziqi.cn/Article/details/gt2vqqcgptw.html

TS:   arr.map(String)
来源：http://dali.yvedp.cn/Article/details/gt2umupomwo.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.gogol.net.cn/Article/details/gt2djacbapa.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhongyouzk.top/Article/details/gt2jqhsbjhs.html

Ruby: arr.map(&:upcase)
来源：http://dali.daxiang520.top/Article/details/gt2vwfxjmxf.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kqrpbbxt.html

[C08] 闭包
来源：http://dali.birdmap.top/Article/details/gt2brfsujjo.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yvedp.cn/Article/details/gt2cvikyqla.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.daria6918.cn/Article/details/gt2tgjqiypj.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.redwolf501.top/Article/details/gt2yiscyzvm.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.fengsongda.top/Article/details/gt2pforuaea.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.aibaodan.cn/Article/details/gt2zrqvxuba.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.nanxinkj.top/Article/details/gt2kdscnrjb.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.feifeiyinyue.top/Article/details/gt2dtzoiqkn.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.gaohongyu789.top/Article/details/gt2tjqhtkfg.html

[C09] 递归
来源：http://dali.hnqzz.top/Article/details/gt2cflsnnao.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.bjfxy.top/Article/details/gt2ftejcilv.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.haohaochexian.top/Article/details/gt2zgujrshd.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gaohongyu789.top/Article/details/gt2evgpnofl.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ybcxt.top/Article/details/gt2reuwfrut.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.dianchejie.cn/Article/details/gt2tqbkrflu.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.redwolf501.top/Article/details/gt2kjpeosed.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.cucudq.cn/Article/details/gt2btcpcryj.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.aizwys.cn/Article/details/gt2iaauuuwb.html

[C10] 变量作用域
来源：http://dali.tianlin.xyz/Article/details/gt2dfnvmflf.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hammf.cn/Article/details/gt2sapuggvv.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yj20258.top/Article/details/gt2sphicabk.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.cashguo.top/Article/details/gt2vggumrvk.html

TS:   同 JS
来源：http://dali.dianchejie.cn/Article/details/gt2spaentla.html

Java: 方法内为块级作用域
来源：http://dali.jlsjyb.cn/Article/details/gt2hntkdvct.html

Go:   花括号块级作用域
来源：http://dali.ydzc1.top/Article/details/gt2dltxokue.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhoulong.xyz/Article/details/gt2gdswuhjl.html

C#:   块级作用域
来源：http://dali.yonumen.top/Article/details/gt2vyxrxheo.html

[C11] 模块导入与导出
来源：http://dali.shuidangran.top/Article/details/gt2dmtkssup.html

Py:   from module import func
来源：http://dali.nanxuanxn.top/Article/details/gt2nuokbepw.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.mhx1999.top/Article/details/gt2bjajgphu.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhixingplan.top/Article/details/gt2drmxwumj.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yonumen.top/Article/details/gt2ooqcukbv.html

Java: import java.util.List;
来源：http://dali.svipenyu.cn/Article/details/gt2gkupfabu.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.aizwys.cn/Article/details/gt2xuszsnbx.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.feifeiyinyue.top/Article/details/gt2tpetfubx.html

C#:   using System.Text;
来源：http://dali.hnqzz.top/Article/details/gt2zcagfdsn.html

[C12] 立即执行函数 IIFE
来源：http://dali.kuanghao11.cn/Article/details/gt2fdevzkdk.html

Py:   (lambda: print("run"))()
来源：http://dali.hammf.cn/Article/details/gt2zludmjeu.html


<!-- 参考信息 -->