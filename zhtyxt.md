代发 wailian999

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.yuanzhike.top/Article/details/gt2ogbtmrbz.html

Java: (int) 'A'; (char) 65
来源：http://dali.yuxming.cn/Article/details/gt2lahzmolt.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.yuanzhike.top/Article/details/gt2xabfvhnw.html

Ruby: "A".ord; 65.chr
来源：http://dali.cheryme.top/Article/details/gt2nxktktyh.html

C#:   (int)'A'; (char)65
来源：http://dali.shzxlz.cn/Article/details/gt2qynausyy.html

[A19] 交换两个变量
来源：http://dali.meibo888.top/Article/details/gt2fllvkytb.html

Py:   a, b = b, a
来源：http://dali.jlsjyb.cn/Article/details/gt2umkvcxxp.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.kuanghao11.cn/Article/details/gt2iiobhnlg.html

JS:   [a, b] = [b, a];
来源：http://dali.zhoulong.xyz/Article/details/gt2wecisxut.html

TS:   [a, b] = [b, a];
来源：http://dali.andypj.xyz/Article/details/gt2eyosunnk.html

Java: int t = a; a = b; b = t;
来源：http://dali.gzhubu.top/Article/details/gt2xskgjnjj.html

Go:   a, b = b, a
来源：http://dali.yj20258.top/Article/details/gt2fbskrcvh.html

Ruby: a, b = b, a
来源：http://dali.xziqi.cn/Article/details/gt2iiftrhsg.html

C#:   (a, b) = (b, a);
来源：http://dali.yongpay.top/Article/details/gt2grsejsxv.html

[A20] 读取标准输入
来源：http://dali.guowangkeji.top/Article/details/gt2wljvgtpf.html

Py:   name = input("请输入：")
来源：http://dali.haohaochexian.top/Article/details/gt2sxzlnazl.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.hnqzz.top/Article/details/gt2mcqklluh.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.ehwqpu.com/Article/details/gt2vhsjgwnl.html

TS:   // Node.js：readline 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2vbyzwnol.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.ydzc1.top/Article/details/gt2tykypdvi.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.cqqwz.cn/Article/details/gt2nqumtbzq.html

Ruby: gets.chomp
来源：http://dali.snrcjt.cn/Article/details/gt2djjzqcop.html

C#:   Console.ReadLine();
来源：http://dali.sxryk.cn/Article/details/gt2olmlcpnq.html

[A21] 保留指定小数位输出
来源：http://dali.gzhubu.top/Article/details/gt2dxcbiuid.html

Py:   f"{3.14159:.2f}"
来源：http://dali.guannengcc.top/Article/details/gt2mdgngirz.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.haohaochexian.top/Article/details/gt2wagnfzje.html

JS:   (3.14159).toFixed(2)
来源：http://dali.yonumen.top/Article/details/gt2plchbile.html

TS:   (3.14159).toFixed(2)
来源：http://dali.nanxuanxn.top/Article/details/gt2hsfisypq.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.zhengqikj.top/Article/details/gt2oqgndmao.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.sxryk.cn/Article/details/gt2yuqnjelo.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.zhixingplan.top/Article/details/gt2crknhyrb.html

C#:   3.14159.ToString("F2")
来源：http://dali.xinyue.icu/Article/details/gt2pjkmyxcy.html

[A22] 获取字符串长度
来源：http://dali.gotoacloud.top/Article/details/gt2qjvkndyr.html

Py:   len(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2nlvoqmzm.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.hammf.cn/Article/details/gt2avsfpwsr.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.dashuyun.cn/Article/details/gt2nfwycfmp.html

TS:   s.length
来源：http://dali.ybcxt.top/Article/details/gt2nsfpnlmu.html

Java: s.length()
来源：http://dali.guannengcc.top/Article/details/gt2kahmtvok.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hqargcge.html

Ruby: s.length
来源：http://dali.wangshuangyany.cn/Article/details/gt2msuxuvsk.html

C#:   s.Length
来源：http://dali.zhengqikj.top/Article/details/gt2tcjeqctu.html

[A23] 大小写转换
来源：http://dali.shuidangran.top/Article/details/gt2ehttzsmc.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.zhengqikj.top/Article/details/gt2slkemduu.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2hsbdiona.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yuxming.cn/Article/details/gt2xoyefuil.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.hongshengwenyu.top/Article/details/gt2ntaygamy.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.yj20258888.top/Article/details/gt2jvsrgxfk.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.hnqzz.top/Article/details/gt2mqyihtwh.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.0kj1m.cn/Article/details/gt2yrjsyapm.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.hywenlv.cn/Article/details/gt2drrqeskl.html

[A24] 去除首尾空白
来源：http://dali.hnqzz.top/Article/details/gt2mywrjkzh.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.sysykeji.top/Article/details/gt2tugcjukz.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2toutrxqm.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.chenjidiqi.icu/Article/details/gt2bgmgkcjj.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.shuidangran.top/Article/details/gt2djndjirx.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.gogol.net.cn/Article/details/gt2pyryocvq.html

Go:   strings.TrimSpace(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bfmebacc.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.kuanghao11.cn/Article/details/gt2gcwqbclg.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.xziqi.cn/Article/details/gt2kocbngrp.html

[A25] 字符串比较
来源：http://dali.tanke756.top/Article/details/gt2dbcaujhe.html

Py:   s1 == s2; s1 != s2
来源：http://dali.jiagoushi.top/Article/details/gt2psthpboh.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.wangdashe.top/Article/details/gt2rvgaqlxh.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2qneygjii.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.aibaodan.cn/Article/details/gt2wtbbdrvk.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.chenzaomai.com/Article/details/gt2ncuafsmu.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.zhongyouzk.top/Article/details/gt2nmsuoqqf.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.jyoumei.cn/Article/details/gt2agxpolvk.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.yuanzhike.top/Article/details/gt2pnnoaxiv.html

[A26] 类型转换总览
来源：http://dali.zhiwuduotai.top/Article/details/gt2cwcykcog.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.xuetiantiany.cn/Article/details/gt2rqisbqqw.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.tianlin.xyz/Article/details/gt2snmhjfeu.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.quarkkingdee.top/Article/details/gt2vehxtsdp.html

TS:   Number() String() Boolean() x as number
来源：http://dali.zhongyouzk.top/Article/details/gt2frkdurwq.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.hywenlv.cn/Article/details/gt2gvjdpwvm.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.hnxiangtu.top/Article/details/gt2gghcmxqu.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.dashuyun.cn/Article/details/gt2sjmcpqzh.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.316326.xyz/Article/details/gt2xdnupqgf.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2ikinsika.html

B. 流程控制
来源：http://dali.hnxiangtu.top/Article/details/gt2aiugeswl.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lnipmdca.html

[B01] 条件判断 if / else
来源：http://dali.vqdsnc.cn/Article/details/gt2vlohbcgn.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.kuanghao11.cn/Article/details/gt2sttawekv.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.havefunace.top/Article/details/gt2odvdmdde.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yonumen.top/Article/details/gt2shslhqbz.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.daria6918.cn/Article/details/gt2cgjnvkmk.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.hywenlv.cn/Article/details/gt2sixovmpv.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.xylfe.cn/Article/details/gt2fmvzgevi.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.sufxvd.cn/Article/details/gt2sipoymau.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.havefunace.top/Article/details/gt2kodsuhuv.html

[B02] 多分支 else if / elif
来源：http://dali.shzxlz.cn/Article/details/gt2epbnqqxi.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.ydzc1.top/Article/details/gt2gnzmblqo.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.yuanzhike.top/Article/details/gt2dfsnjlsb.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.tianlin.xyz/Article/details/gt2kjczlqks.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.snrcjt.cn/Article/details/gt2ubxmqneo.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yuxming.cn/Article/details/gt2jnbncsgc.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.chenjidiqi.icu/Article/details/gt2uxgwtcmz.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.zhoulong.xyz/Article/details/gt2msdnxjag.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hjbpmbkx.html

[B03] switch / match / case
来源：http://dali.tanke756.top/Article/details/gt2psmontme.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.gotoacloud.top/Article/details/gt2xbzkwcez.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.zhixingplan.top/Article/details/gt2dgcgoagq.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2poqmofcn.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.tanke756.top/Article/details/gt2zlumztgg.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.jqgfzy.top/Article/details/gt2zaqtjjad.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.yj20258888.top/Article/details/gt2lkgodhfq.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.ivvv.top/Article/details/gt2lkbnqbfs.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sxurvujj.html

[B04] for 计数循环
来源：http://dali.jinghuilouyu.cn/Article/details/gt2faidugfp.html

Py:   for i in range(10): print(i)
来源：http://dali.redwolf501.top/Article/details/gt2brogugko.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.jianghu66.top/Article/details/gt2qmfrdeun.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zdqjudy.top/Article/details/gt2ewmithlv.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.daria6918.cn/Article/details/gt2ctcrhfau.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.gaohongyu789.top/Article/details/gt2yqsubjko.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.yangfankeji.com/Article/details/gt2blculgak.html

Ruby: 10.times { |i| puts i }
来源：http://dali.pengpengdd.cyou/Article/details/gt2dtwwxbtp.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.smart0.xyz/Article/details/gt2ykmabfeb.html

[B05] 遍历数组 / 列表
来源：http://dali.cashguo.top/Article/details/gt2wyxuntgc.html

Py:   for item in arr: print(item)
来源：http://dali.jiagoushi.top/Article/details/gt2ombjhhlx.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2dhjqtbme.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.cheryme.top/Article/details/gt2ghuqgjwu.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fnaesapi.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.hnxiangtu.top/Article/details/gt2absxrlyv.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.ydzc1.top/Article/details/gt2pwvbejyr.html

Ruby: arr.each { |item| puts item }
来源：http://dali.ydzc1.top/Article/details/gt2avfvsoka.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jiagoushi.top/Article/details/gt2gxnftdsk.html

[B06] 遍历字典 / 对象
来源：http://dali.havefunace.top/Article/details/gt2wgakkphp.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.zhengqikj.top/Article/details/gt2vmsktdbi.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqozjafg.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2smvhapxb.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.cheryme.top/Article/details/gt2xnlgmuzp.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.andypj.xyz/Article/details/gt2zvufghqu.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.hammf.cn/Article/details/gt2ruskqvjr.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.gogol.net.cn/Article/details/gt2xntiehko.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.gogol.net.cn/Article/details/gt2uqiixheh.html

[B07] while 循环
来源：http://dali.zycfv.cn/Article/details/gt2ctgortuu.html

Py:   while i < 10: i += 1
来源：http://dali.ydzc1.top/Article/details/gt2zzmroadr.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.shuidangran.top/Article/details/gt2evyezywc.html

JS:   while (i < 10) { i++; }
来源：http://dali.chenzaomai.com/Article/details/gt2xkryjcha.html

TS:   while (i < 10) { i++; }
来源：http://dali.cdnleiting.top/Article/details/gt2fhpkdmtr.html

Java: while (i < 10) { i++; }
来源：http://dali.hfpthk.cn/Article/details/gt2fhztqoma.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.aibaodan.cn/Article/details/gt2hxvvxqkh.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zhoulong.xyz/Article/details/gt2vcrdghaj.html

C#:   while (i < 10) { i++; }
来源：http://dali.smart0.xyz/Article/details/gt2egzxqtrf.html

[B08] do-while（至少执行一次）
来源：http://dali.gotoacloud.top/Article/details/gt2iswlqqyt.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.daxiang520.top/Article/details/gt2gskbrddb.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.gogol.net.cn/Article/details/gt2htcvofdo.html

JS:   do { i++; } while (i < 10);
来源：http://dali.daxiang520.top/Article/details/gt2uhnmxkrn.html

TS:   do { i++; } while (i < 10);
来源：http://dali.aizwys.cn/Article/details/gt2mwgabvva.html

Java: do { i++; } while (i < 10);
来源：http://dali.daxiang520.top/Article/details/gt2lizslbec.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.shzxlz.cn/Article/details/gt2vqsnpwbv.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.sweek.top/Article/details/gt2rftzbhqs.html

C#:   do { i++; } while (i < 10);
来源：http://dali.c1oappe.top/Article/details/gt2fqlgdlyn.html

[B09] break 与 continue
来源：http://dali.ppjwa.cn/Article/details/gt2yzkdrlgw.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.andypj.xyz/Article/details/gt2qvagbhku.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.chenlongwang.top/Article/details/gt2mctpuzhp.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinqigufen.top/Article/details/gt2dsuubqmx.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenlongwang.top/Article/details/gt2mutsmnhd.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.bjfxy.top/Article/details/gt2adovyvny.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jqgfzy.top/Article/details/gt2yhqinosu.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhengqikj.top/Article/details/gt2gurigigv.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yangfankeji.com/Article/details/gt2cbmpcgiq.html

[B10] 遍历同时拿索引
来源：http://dali.redwolf501.top/Article/details/gt2ekbnhlol.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.svipenyu.cn/Article/details/gt2tdpqgyyc.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.sysykeji.top/Article/details/gt2rucgzqwh.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.pengpengdd.cyou/Article/details/gt2yxhljwfw.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.316326.xyz/Article/details/gt2awwhulmr.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.aizwys.cn/Article/details/gt2fdexbfrx.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.sweek.top/Article/details/gt2bvorqjkt.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.cdnleiting.top/Article/details/gt2rxibdzda.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.kuanghao11.cn/Article/details/gt2dbndkxva.html

[B11] 生成数字序列 / 区间
来源：http://dali.pycfn.com/Article/details/gt2ajmhwcan.html

Py:   list(range(0, 10, 2))
来源：http://dali.jyoumei.cn/Article/details/gt2ytzznnbs.html

PHP:  range(0, 10, 2);
来源：http://dali.nanxinkj.top/Article/details/gt2qjeomptm.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xinyue.icu/Article/details/gt2xuprdwxe.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.fzhhl.top/Article/details/gt2wpyyhtzr.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fvhtyluv.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.fengsongda.top/Article/details/gt2yovasztk.html

Ruby: (0...10).step(2).to_a
来源：http://dali.sufxvd.cn/Article/details/gt2cmexhzat.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yangfankeji.com/Article/details/gt2lujywahi.html

[B12] 跳出多层循环
来源：http://dali.dianchejie.cn/Article/details/gt2gxjiyhit.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.dianchejie.cn/Article/details/gt2lxvoxnwg.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.gogol.net.cn/Article/details/gt2afgfxeuv.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.wangshuangyany.cn/Article/details/gt2rmpqxnqo.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.aizwys.cn/Article/details/gt2kjzujzos.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhongyouzk.top/Article/details/gt2dlvqvecm.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.meibo888.top/Article/details/gt2njgiejif.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yj202588.top/Article/details/gt2plsxlpxl.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yoryuwli.html

[B13] 判断是否为数字
来源：http://dali.redwolf501.top/Article/details/gt2bmiejdmz.html

Py:   isinstance(x, (int, float))
来源：http://dali.vqdsnc.cn/Article/details/gt2azdilyuk.html

PHP:  is_numeric($x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nkglzjeh.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.tianlin.xyz/Article/details/gt2oraqjfci.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hfpthk.cn/Article/details/gt2mluabshp.html

Java: x instanceof Number
来源：http://dali.jinqigfzy.top/Article/details/gt2icldkmao.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.tianlin.xyz/Article/details/gt2uajuouiv.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhengqikj.top/Article/details/gt2ysbvvwcl.html

C#:   x is int or double or decimal
来源：http://dali.sufxvd.cn/Article/details/gt2djonwucm.html

[B14] 判断值是否在集合内
来源：http://dali.mhx1999.top/Article/details/gt2zshjnjep.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.ppjwa.cn/Article/details/gt2nazcacrd.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.redwolf501.top/Article/details/gt2evgthgvz.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.quarkkingdee.top/Article/details/gt2dwzweoxu.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.dashuyun.cn/Article/details/gt2dbkagasw.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jyoumei.cn/Article/details/gt2fkhpmfiy.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.wangdashe.top/Article/details/gt2mnpqjepm.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgtfiwjm.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yuanzhike.top/Article/details/gt2hlssctaa.html

[B15] 布尔运算与取反
来源：http://dali.daria6918.cn/Article/details/gt2vgofjmae.html

Py:   a and b or not c
来源：http://dali.jianghu66.top/Article/details/gt2estdwmgz.html

PHP:  $a && $b || !$c
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tksctyqo.html

JS:   a && b || !c
来源：http://dali.yj20258.top/Article/details/gt2xymdoins.html

TS:   a && b || !c
来源：http://dali.gzhubu.top/Article/details/gt2dyrrmehm.html

Java: a && b || !c
来源：http://dali.ppjwa.cn/Article/details/gt2jyckauuk.html

Go:   a && b || !c
来源：http://dali.xuanzx.com/Article/details/gt2mseelemx.html

Ruby: a && b || !c
来源：http://dali.guowangkeji.top/Article/details/gt2jcxupppj.html

C#:   a && b || !c
来源：http://dali.tanke756.top/Article/details/gt2nxgypcxp.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jlsjyb.cn/Article/details/gt2tplwumhv.html

Py:   if not data: return
来源：http://dali.aibaodan.cn/Article/details/gt2ejqzisiw.html

PHP:  if (!$data) { return; }
来源：http://dali.sufxvd.cn/Article/details/gt2kaykcouh.html

JS:   if (!data) return;
来源：http://dali.yj20258888.top/Article/details/gt2zixymofh.html

TS:   if (!data) return;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gdufvcza.html

Java: if (data == null) return;
来源：http://dali.9152youxi.cn/Article/details/gt2btcdtloq.html

Go:   if data == nil { return }
来源：http://dali.cashguo.top/Article/details/gt2qgskiogs.html

Ruby: return if data.nil?
来源：http://dali.zhiwuduotai.top/Article/details/gt2nydacmsv.html

C#:   if (data == null) return;
来源：http://dali.jqgufenzy.top/Article/details/gt2rywrrnze.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2isnubbws.html

C. 函数与作用域
来源：http://dali.xziqi.cn/Article/details/gt2evmfhgwk.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2rmywbnnh.html

[C01] 定义函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pkpjdyzy.html

Py:   def add(a, b): return a + b
来源：http://dali.gogol.net.cn/Article/details/gt2njarvitw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hywenlv.cn/Article/details/gt2qaizkhml.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zycfv.cn/Article/details/gt2yqlcfqbl.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.dianchejie.cn/Article/details/gt2eolofivs.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2coqwpvny.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yj20258888.top/Article/details/gt2gidymjum.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fdrrmqjc.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.guannengcc.top/Article/details/gt2wumxvyev.html

[C02] 默认参数
来源：http://dali.sysykeji.top/Article/details/gt2aqguyumy.html

Py:   def greet(name="World"): return name
来源：http://dali.dianchejie.cn/Article/details/gt2iuivshbh.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.ehwqpu.com/Article/details/gt2awnscddh.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.cqqwz.cn/Article/details/gt2uknbhqnd.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.ppjwa.cn/Article/details/gt2efajjren.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhoulong.xyz/Article/details/gt2vxxppnqz.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.xuanzx.com/Article/details/gt2fsmeyhvg.html

Ruby: def greet(name = "World") = name
来源：http://dali.smart0.xyz/Article/details/gt2eiqvwtqt.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yanxiufei.cn/Article/details/gt2moudpkbt.html

[C03] 可变参数
来源：http://dali.chenlongwang.top/Article/details/gt2rdsvwwhf.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhongyouzk.top/Article/details/gt2dltljwwt.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2mneldmwb.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2nasvcnpa.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ppjwa.cn/Article/details/gt2viyeasee.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lfqvudzu.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.tian-w.cn/Article/details/gt2iavugukc.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.sxryk.cn/Article/details/gt2gbaqcgyj.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.nanxinkj.top/Article/details/gt2ihcbktzk.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yonumen.top/Article/details/gt2bihdnefc.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.xuanzx.com/Article/details/gt2gegjvyfz.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xuanzx.com/Article/details/gt2xornxpxt.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.dashuyun.cn/Article/details/gt2ldjwxjdr.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.gotoacloud.top/Article/details/gt2xbydvqpe.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.nanxinkj.top/Article/details/gt2tegsytyt.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhoulong.xyz/Article/details/gt2kjnfepkm.html

Ruby: f(a: 1, b: 2)
来源：http://dali.shzxlz.cn/Article/details/gt2tcoxqrms.html

C#:   f(a: 1, b: 2)
来源：http://dali.guannengcc.top/Article/details/gt2kqlgxnqn.html

[C05] 返回多个值
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pgijbmkl.html

Py:   return a, b
来源：http://dali.svipenyu.cn/Article/details/gt2jydglonn.html

PHP:  return [$a, $b];
来源：http://dali.redwolf501.top/Article/details/gt2imgocagg.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.fzhhl.top/Article/details/gt2makaollf.html

TS:   return { a, b };
来源：http://dali.hysaishi.cn/Article/details/gt2ubysmhnu.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.aibaodan.cn/Article/details/gt2fwniczhr.html

Go:   return a, b
来源：http://dali.cheryme.top/Article/details/gt2mftjorlw.html

Ruby: return a, b
来源：http://dali.smart0.xyz/Article/details/gt2pyvzhcus.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cijmvrip.html

[C06] 匿名函数 / lambda
来源：http://dali.wangshuangyany.cn/Article/details/gt2ghphnofl.html

Py:   square = lambda x: x * x
来源：http://dali.jlsjyb.cn/Article/details/gt2fwybwyql.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.guowangkeji.top/Article/details/gt2awqjdgeo.html

JS:   const square = x => x * x;
来源：http://dali.fengsongda.top/Article/details/gt2dsihxabs.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.guannengcc.top/Article/details/gt2dcpwetkj.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.c1oappe.top/Article/details/gt2loatotqc.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yj20258.top/Article/details/gt2jbnmphtc.html

Ruby: square = ->(x) { x * x }
来源：http://dali.0kj1m.cn/Article/details/gt2tqxtlbbl.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.chenlongwang.top/Article/details/gt2ddguqopt.html

[C07] 把函数作为参数传入
来源：http://dali.yueranfly.top/Article/details/gt2zscwvmrp.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.wangshuangyany.cn/Article/details/gt2nkwiphri.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.tian-w.cn/Article/details/gt2ruwualch.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.aizwys.cn/Article/details/gt2tnapjiky.html

TS:   arr.map(String)
来源：http://dali.gzhubu.top/Article/details/gt2bbqxitvd.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.andypj.xyz/Article/details/gt2hoefpczj.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jlsjyb.cn/Article/details/gt2woyqyfrp.html

Ruby: arr.map(&:upcase)
来源：http://dali.havefunace.top/Article/details/gt2hqvtbmvs.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.andypj.xyz/Article/details/gt2mhkzvxck.html

[C08] 闭包
来源：http://dali.svipenyu.cn/Article/details/gt2awowfapi.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hywenlv.cn/Article/details/gt2jmdtvspx.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.cucudq.cn/Article/details/gt2ffcjeybr.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.dianchejie.cn/Article/details/gt2ekrraryl.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hnqzz.top/Article/details/gt2ytkidjlb.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ypkpzgkk.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.nanxinkj.top/Article/details/gt2qkadqdvb.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bcwobhyc.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jqgufenzy.top/Article/details/gt2jerqtwky.html

[C09] 递归
来源：http://dali.nanxuanxn.top/Article/details/gt2xvmbcsoi.html


<!-- 参考信息 -->