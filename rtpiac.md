代发 wailian999

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.316326.xyz/Article/details/gt2eamyzhbl.html

Java: (int) 'A'; (char) 65
来源：http://dali.andypj.xyz/Article/details/gt2gmuommcf.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.xuanzx.com/Article/details/gt2ihiiactm.html

Ruby: "A".ord; 65.chr
来源：http://dali.zycfv.cn/Article/details/gt2wrlyeyna.html

C#:   (int)'A'; (char)65
来源：http://dali.hnxiangtu.top/Article/details/gt2xhnujhmk.html

[A19] 交换两个变量
来源：http://dali.yuanzhike.top/Article/details/gt2mmdngyop.html

Py:   a, b = b, a
来源：http://dali.guowangkeji.top/Article/details/gt2ifdrepta.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2riotbgsx.html

JS:   [a, b] = [b, a];
来源：http://dali.yj20258.top/Article/details/gt2bepujsys.html

TS:   [a, b] = [b, a];
来源：http://dali.shuidangran.top/Article/details/gt2sytvqaqx.html

Java: int t = a; a = b; b = t;
来源：http://dali.dashuyun.cn/Article/details/gt2daafkspo.html

Go:   a, b = b, a
来源：http://dali.tanke756.top/Article/details/gt2evubogbo.html

Ruby: a, b = b, a
来源：http://dali.andypj.xyz/Article/details/gt2esyxpywu.html

C#:   (a, b) = (b, a);
来源：http://dali.chenzaomai.com/Article/details/gt2rxhbigee.html

[A20] 读取标准输入
来源：http://dali.zhixingplan.top/Article/details/gt2nppvnybd.html

Py:   name = input("请输入：")
来源：http://dali.ybcxt.top/Article/details/gt2itidcajd.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.gogol.net.cn/Article/details/gt2unpsjird.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.wangshuangyany.cn/Article/details/gt2temtikin.html

TS:   // Node.js：readline 模块
来源：http://dali.meibo888.top/Article/details/gt2ezwustut.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.gaohongyu789.top/Article/details/gt2jyewdhdu.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.xylfe.cn/Article/details/gt2rtsjzmbc.html

Ruby: gets.chomp
来源：http://dali.yonumen.top/Article/details/gt2assghzfr.html

C#:   Console.ReadLine();
来源：http://dali.yj20258888.top/Article/details/gt2aiybvlwj.html

[A21] 保留指定小数位输出
来源：http://dali.meibo888.top/Article/details/gt2xhgbbizw.html

Py:   f"{3.14159:.2f}"
来源：http://dali.pengpengdd.cyou/Article/details/gt2zxalfnsy.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.9152youxi.cn/Article/details/gt2aujhekff.html

JS:   (3.14159).toFixed(2)
来源：http://dali.aizwys.cn/Article/details/gt2lhzhwqya.html

TS:   (3.14159).toFixed(2)
来源：http://dali.jinqigufen.top/Article/details/gt2bllxzmsq.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.birdmap.top/Article/details/gt2beiekhgj.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.cdnleiting.top/Article/details/gt2prwqmnei.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.hnqzz.top/Article/details/gt2cuczyhvp.html

C#:   3.14159.ToString("F2")
来源：http://dali.316326.xyz/Article/details/gt2znymbuhv.html

[A22] 获取字符串长度
来源：http://dali.daxiang520.top/Article/details/gt2cszeatsu.html

Py:   len(s)
来源：http://dali.guannengcc.top/Article/details/gt2omzabrst.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.316326.xyz/Article/details/gt2pleanygv.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.gaohongyu789.top/Article/details/gt2rcdukmzn.html

TS:   s.length
来源：http://dali.kuanghao11.cn/Article/details/gt2fyzesgmf.html

Java: s.length()
来源：http://dali.hammf.cn/Article/details/gt2uihkhvuy.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.shzxlz.cn/Article/details/gt2wprafyqc.html

Ruby: s.length
来源：http://dali.tianlin.xyz/Article/details/gt2raondufa.html

C#:   s.Length
来源：http://dali.aizwys.cn/Article/details/gt2kxbujvqr.html

[A23] 大小写转换
来源：http://dali.fzhhl.top/Article/details/gt2mneqrtph.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.ppjwa.cn/Article/details/gt2eajqreoe.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.gzhubu.top/Article/details/gt2swizriie.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.dianchejie.cn/Article/details/gt2imvuaerw.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.sweek.top/Article/details/gt2nsaouccc.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.bjfxy.top/Article/details/gt2sazumelj.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.ppjwa.cn/Article/details/gt2fmbigahh.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.zhongyouzk.top/Article/details/gt2pebnbecd.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.sysykeji.top/Article/details/gt2serlnwsy.html

[A24] 去除首尾空白
来源：http://dali.hnqzz.top/Article/details/gt2gjglleni.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2prhygcca.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.birdmap.top/Article/details/gt2leqfnlgy.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.dashuyun.cn/Article/details/gt2uwypiaiq.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.gaohongyu789.top/Article/details/gt2lhstzlny.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.daria6918.cn/Article/details/gt2zbfznlea.html

Go:   strings.TrimSpace(s)
来源：http://dali.hysaishi.cn/Article/details/gt2dakzofmp.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.gaohongyu789.top/Article/details/gt2rcfycvyd.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.quarkkingdee.top/Article/details/gt2wezeewfj.html

[A25] 字符串比较
来源：http://dali.tanke756.top/Article/details/gt2cbqrcvqg.html

Py:   s1 == s2; s1 != s2
来源：http://dali.yonumen.top/Article/details/gt2fzjezshv.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.quarkkingdee.top/Article/details/gt2eaeyzcyw.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.xylfe.cn/Article/details/gt2zxuvflhp.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.tianlin.xyz/Article/details/gt2bwtugvij.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.haohaochexian.top/Article/details/gt2chrspykv.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.sweek.top/Article/details/gt2vrvbythq.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.zhiwuduotai.top/Article/details/gt2ijpoftah.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.jyoumei.cn/Article/details/gt2eipwkzsf.html

[A26] 类型转换总览
来源：http://dali.zdqjudy.top/Article/details/gt2rgrsjbvn.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.zhongyouzk.top/Article/details/gt2ccnmyarc.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ypejiwml.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.zhijiandao.cn/Article/details/gt2pxcmjvmo.html

TS:   Number() String() Boolean() x as number
来源：http://dali.hysaishi.cn/Article/details/gt2bihnuymv.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tewoxgxl.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.c1oappe.top/Article/details/gt2sfxhykho.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.zhongyouzk.top/Article/details/gt2rwxekmwv.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.sysykeji.top/Article/details/gt2ihvmmdnc.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2yzfaxwka.html

B. 流程控制
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bcvrokga.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2yqssoudb.html

[B01] 条件判断 if / else
来源：http://dali.daxiang520.top/Article/details/gt2znnvzobm.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.hnqzz.top/Article/details/gt2zlvhsxta.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.shuidangran.top/Article/details/gt2fdpxhdnh.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ecoctcfz.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.daria6918.cn/Article/details/gt2elftcvst.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.yonumen.top/Article/details/gt2mewhfsyf.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.kuanghao11.cn/Article/details/gt2rxmhokom.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.zycfv.cn/Article/details/gt2cvyjobfo.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.guannengcc.top/Article/details/gt2apzzwlzz.html

[B02] 多分支 else if / elif
来源：http://dali.yuanzhike.top/Article/details/gt2eevucply.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.pycfn.com/Article/details/gt2xqhweste.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.quarkkingdee.top/Article/details/gt2eieptccm.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.meibo888.top/Article/details/gt2fcyhyurl.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yuxming.cn/Article/details/gt2inirzyzl.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yvedp.cn/Article/details/gt2prkcuvmh.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.guannengcc.top/Article/details/gt2ldvopiwj.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.haohaochexian.top/Article/details/gt2kgcpcyll.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.quarkkingdee.top/Article/details/gt2bmmwhaos.html

[B03] switch / match / case
来源：http://dali.cdnleiting.top/Article/details/gt2poamljrh.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.yangfankeji.com/Article/details/gt2dsiutete.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hywfepfu.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zycfv.cn/Article/details/gt2ajhcilct.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.tianlin.xyz/Article/details/gt2vnjlthjv.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.gzhubu.top/Article/details/gt2ixhtldan.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.cucudq.cn/Article/details/gt2vnvgrjou.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.bjfxy.top/Article/details/gt2beqjakiy.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.hnxiangtu.top/Article/details/gt2jzlhkvtu.html

[B04] for 计数循环
来源：http://dali.hnqzz.top/Article/details/gt2vgfengrr.html

Py:   for i in range(10): print(i)
来源：http://dali.dianchejie.cn/Article/details/gt2mtucodro.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.iojbl.cn/Article/details/gt2nebznnhs.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yj202588.top/Article/details/gt2usqstsyp.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ldmrelxv.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.ydzc1.top/Article/details/gt2jkwctqaa.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.mhx1999.top/Article/details/gt2dsdefmwx.html

Ruby: 10.times { |i| puts i }
来源：http://dali.ppjwa.cn/Article/details/gt2nnpuetxm.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.daria6918.cn/Article/details/gt2hbdzjlds.html

[B05] 遍历数组 / 列表
来源：http://dali.yj20258888.top/Article/details/gt2uxzasobg.html

Py:   for item in arr: print(item)
来源：http://dali.jqgufenzy.top/Article/details/gt2qwvybodb.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.kuanghao11.cn/Article/details/gt2hupfavcn.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.guannengcc.top/Article/details/gt2vjvbfbux.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.gotoacloud.top/Article/details/gt2vqafuhba.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.xinyue.icu/Article/details/gt2dkuccqap.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.aibaodan.cn/Article/details/gt2dvqvzlqs.html

Ruby: arr.each { |item| puts item }
来源：http://dali.yongpay.top/Article/details/gt2bucdxyvl.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.yuxming.cn/Article/details/gt2wyrggwef.html

[B06] 遍历字典 / 对象
来源：http://dali.havefunace.top/Article/details/gt2cednuovu.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.nwbrower.top/Article/details/gt2mlzdsmvd.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.zhengqikj.top/Article/details/gt2nybyypul.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ywcfsify.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jiagoushi.top/Article/details/gt2stpjakjc.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.svipenyu.cn/Article/details/gt2yalusnfx.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.redwolf501.top/Article/details/gt2eevdfnhn.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.ehwqpu.com/Article/details/gt2lqopbzva.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.chenlongwang.top/Article/details/gt2mpowaixy.html

[B07] while 循环
来源：http://dali.jlsjyb.cn/Article/details/gt2zqnkyqbk.html

Py:   while i < 10: i += 1
来源：http://dali.ppjwa.cn/Article/details/gt2rwayvmut.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.daria6918.cn/Article/details/gt2qvcqefmq.html

JS:   while (i < 10) { i++; }
来源：http://dali.yj20258888.top/Article/details/gt2pefocljk.html

TS:   while (i < 10) { i++; }
来源：http://dali.hysaishi.cn/Article/details/gt2ozcnxupq.html

Java: while (i < 10) { i++; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2vosuzrdh.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.meibo888.top/Article/details/gt2lwxldgic.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yvedp.cn/Article/details/gt2oxysriwm.html

C#:   while (i < 10) { i++; }
来源：http://dali.daria6918.cn/Article/details/gt2ufjiqfms.html

[B08] do-while（至少执行一次）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lgxgwyod.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.daxiang520.top/Article/details/gt2xpjjyalp.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.daxiang520.top/Article/details/gt2abpkxeli.html

JS:   do { i++; } while (i < 10);
来源：http://dali.ydzc1.top/Article/details/gt2igyjbmuj.html

TS:   do { i++; } while (i < 10);
来源：http://dali.nanxuanxn.top/Article/details/gt2hzuunguz.html

Java: do { i++; } while (i < 10);
来源：http://dali.yonumen.top/Article/details/gt2jowjispy.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.meibo888.top/Article/details/gt2daenwbxp.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ilgecivo.html

C#:   do { i++; } while (i < 10);
来源：http://dali.tanke756.top/Article/details/gt2bzloikth.html

[B09] break 与 continue
来源：http://dali.zhongyouzk.top/Article/details/gt2rtklhbzm.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.guowangkeji.top/Article/details/gt2foihrfzu.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.haohaochexian.top/Article/details/gt2bvocfrwm.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cqqwz.cn/Article/details/gt2xzkfchbp.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dxqzvlek.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj20258.top/Article/details/gt2qmyhlvco.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.hammf.cn/Article/details/gt2yorscvpb.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.daria6918.cn/Article/details/gt2vmdnmewy.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xuanzx.com/Article/details/gt2jtpibqcf.html

[B10] 遍历同时拿索引
来源：http://dali.gotoacloud.top/Article/details/gt2cnmwnhhy.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.jianghu66.top/Article/details/gt2kurzemwj.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.jlsjyb.cn/Article/details/gt2apmsxgnu.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.birdmap.top/Article/details/gt2avbrgkyc.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.tianlin.xyz/Article/details/gt2ljauefew.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.guowangkeji.top/Article/details/gt2cdwzxnqk.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.ivvv.top/Article/details/gt2mtwjhxrg.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.shuidangran.top/Article/details/gt2riynrzqv.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.nanxinkj.top/Article/details/gt2pnonkduv.html

[B11] 生成数字序列 / 区间
来源：http://dali.fzhhl.top/Article/details/gt2efiolzon.html

Py:   list(range(0, 10, 2))
来源：http://dali.fzhhl.top/Article/details/gt2pdamoqxo.html

PHP:  range(0, 10, 2);
来源：http://dali.zhiwuduotai.top/Article/details/gt2zueabejf.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.kuanghao11.cn/Article/details/gt2xyrxokqv.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yj20258888.top/Article/details/gt2hbdhcqje.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.iojbl.cn/Article/details/gt2eqpvfafj.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.nanxinkj.top/Article/details/gt2uacmobvi.html

Ruby: (0...10).step(2).to_a
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wqsrozeg.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.nanxinkj.top/Article/details/gt2ffliprra.html

[B12] 跳出多层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ilbfhzyd.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.ydzc1.top/Article/details/gt2mzzummnp.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.tianlin.xyz/Article/details/gt2fjvfggdz.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ybcxt.top/Article/details/gt2mudehdyw.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.nwbrower.top/Article/details/gt2xhadfslt.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yuxming.cn/Article/details/gt2hsfgaqtp.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oymyawgs.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.aibaodan.cn/Article/details/gt2oouhwcrq.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.9152youxi.cn/Article/details/gt2nnaxqpoj.html

[B13] 判断是否为数字
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ktihkcud.html

Py:   isinstance(x, (int, float))
来源：http://dali.tianlin.xyz/Article/details/gt2gniquhcr.html

PHP:  is_numeric($x)
来源：http://dali.cqqwz.cn/Article/details/gt2npchqbnj.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yuanzhike.top/Article/details/gt2spsxcfrn.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.wangdashe.top/Article/details/gt2kwilnndi.html

Java: x instanceof Number
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aelokcab.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zdqjudy.top/Article/details/gt2libzvshg.html

Ruby: x.is_a?(Numeric)
来源：http://dali.hnqzz.top/Article/details/gt2slaffdzk.html

C#:   x is int or double or decimal
来源：http://dali.cheryme.top/Article/details/gt2oicmjrik.html

[B14] 判断值是否在集合内
来源：http://dali.gzhubu.top/Article/details/gt2fxgfvaut.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hnxiangtu.top/Article/details/gt2skirveou.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yanxiufei.cn/Article/details/gt2znqllujw.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.andypj.xyz/Article/details/gt2hvrwxotx.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.mhx1999.top/Article/details/gt2eyefmuze.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.pycfn.com/Article/details/gt2sqidoeif.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hywenlv.cn/Article/details/gt2dkptwlvd.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yongpay.top/Article/details/gt2rpivajpy.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zwkgjpwb.html

[B15] 布尔运算与取反
来源：http://dali.ivvv.top/Article/details/gt2ekdktuym.html

Py:   a and b or not c
来源：http://dali.yanxiufei.cn/Article/details/gt2ynrgvljf.html

PHP:  $a && $b || !$c
来源：http://dali.hysaishi.cn/Article/details/gt2jbmqrgnb.html

JS:   a && b || !c
来源：http://dali.andypj.xyz/Article/details/gt2yblfepep.html

TS:   a && b || !c
来源：http://dali.feifeiyinyue.top/Article/details/gt2guaavvzl.html

Java: a && b || !c
来源：http://dali.meibo888.top/Article/details/gt2hhppbfii.html

Go:   a && b || !c
来源：http://dali.cqqwz.cn/Article/details/gt2tebxydhy.html

Ruby: a && b || !c
来源：http://dali.ehwqpu.com/Article/details/gt2fiehngtd.html

C#:   a && b || !c
来源：http://dali.wangshuangyany.cn/Article/details/gt2qwmkkohz.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.hammf.cn/Article/details/gt2gnlyxvgu.html

Py:   if not data: return
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dfujrkox.html

PHP:  if (!$data) { return; }
来源：http://dali.havefunace.top/Article/details/gt2skqvadse.html

JS:   if (!data) return;
来源：http://dali.xinyue.icu/Article/details/gt2wavhipij.html

TS:   if (!data) return;
来源：http://dali.hnqzz.top/Article/details/gt2aldvqkhp.html

Java: if (data == null) return;
来源：http://dali.mhx1999.top/Article/details/gt2erafzbmq.html

Go:   if data == nil { return }
来源：http://dali.dianchejie.cn/Article/details/gt2qripxtxc.html

Ruby: return if data.nil?
来源：http://dali.nanxuanxn.top/Article/details/gt2wgdiaose.html

C#:   if (data == null) return;
来源：http://dali.cdnleiting.top/Article/details/gt2ymczsyqc.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2rvivkzml.html

C. 函数与作用域
来源：http://dali.wangdashe.top/Article/details/gt2wmxiudrs.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2yujuyrbp.html

[C01] 定义函数
来源：http://dali.jqgufenzy.top/Article/details/gt2atkknfif.html

Py:   def add(a, b): return a + b
来源：http://dali.xziqi.cn/Article/details/gt2jzrzkejo.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cheryme.top/Article/details/gt2qjlxrpun.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gt2cdpargmn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hywenlv.cn/Article/details/gt2odqxpanq.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.cqqwz.cn/Article/details/gt2pnwaxpdm.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.chenlongwang.top/Article/details/gt2ltwjlgvu.html

Ruby: def add(a, b); a + b; end
来源：http://dali.chenzaomai.com/Article/details/gt2fjlmamma.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.gaohongyu789.top/Article/details/gt2addghbxh.html

[C02] 默认参数
来源：http://dali.yj20258888.top/Article/details/gt2jhjvwyyw.html

Py:   def greet(name="World"): return name
来源：http://dali.cucudq.cn/Article/details/gt2vzmtvlid.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.cashguo.top/Article/details/gt2ztlxipux.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.tianlin.xyz/Article/details/gt2cslxojhf.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yonumen.top/Article/details/gt2ysimzbvp.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yj202588.top/Article/details/gt2nydlslzh.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.gaohongyu789.top/Article/details/gt2qvynigco.html

Ruby: def greet(name = "World") = name
来源：http://dali.yj202588.top/Article/details/gt2lxhrtzxk.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.pengpengdd.cyou/Article/details/gt2lwphzqhn.html

[C03] 可变参数
来源：http://dali.kuanghao11.cn/Article/details/gt2bzughuhq.html

Py:   def total(*args): return sum(args)
来源：http://dali.hysaishi.cn/Article/details/gt2qgfidsku.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.tianlin.xyz/Article/details/gt2bgdyldul.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.meibo888.top/Article/details/gt2kuyntiqo.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cashguo.top/Article/details/gt2esucrsfq.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.316326.xyz/Article/details/gt2tccbimsh.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ppjwa.cn/Article/details/gt2jiufqxai.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jyoumei.cn/Article/details/gt2jesmnfut.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.ivvv.top/Article/details/gt2cuadwowp.html

[C04] 命名参数 / 关键字参数
来源：http://dali.xinyue.icu/Article/details/gt2yzskjisj.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.cqqwz.cn/Article/details/gt2kjnomvty.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.aizwys.cn/Article/details/gt2iywlptbd.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yj20258.top/Article/details/gt2nhmwshnt.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.birdmap.top/Article/details/gt2caymfaxi.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jiagoushi.top/Article/details/gt2mssqehhu.html

Go:   // 无：用配置结构体参数
来源：http://dali.ybcxt.top/Article/details/gt2ahpgmqrv.html

Ruby: f(a: 1, b: 2)
来源：http://dali.smart0.xyz/Article/details/gt2gewopeah.html

C#:   f(a: 1, b: 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nuhiaarw.html

[C05] 返回多个值
来源：http://dali.gotoacloud.top/Article/details/gt2bbulkopk.html

Py:   return a, b
来源：http://dali.jinqigufen.top/Article/details/gt2petweuoy.html

PHP:  return [$a, $b];
来源：http://dali.sweek.top/Article/details/gt2bsujannc.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.ehwqpu.com/Article/details/gt2wsprwycu.html

TS:   return { a, b };
来源：http://dali.shangyingyoupin.top/Article/details/gt2leecyrgz.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.dianchejie.cn/Article/details/gt2yiulebye.html

Go:   return a, b
来源：http://dali.fengsongda.top/Article/details/gt2mkbvezbu.html

Ruby: return a, b
来源：http://dali.snrcjt.cn/Article/details/gt2yqaqxbup.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.pycfn.com/Article/details/gt2kvdapiir.html

[C06] 匿名函数 / lambda
来源：http://dali.ppjwa.cn/Article/details/gt2cwieghcz.html

Py:   square = lambda x: x * x
来源：http://dali.cqqwz.cn/Article/details/gt2ubqkkbwo.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.pycfn.com/Article/details/gt2xbvnpntk.html

JS:   const square = x => x * x;
来源：http://dali.tianlin.xyz/Article/details/gt2rzclqdfn.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.tian-w.cn/Article/details/gt2kagvjtap.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.shzxlz.cn/Article/details/gt2psekipif.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yuxming.cn/Article/details/gt2fneygiyf.html

Ruby: square = ->(x) { x * x }
来源：http://dali.cucudq.cn/Article/details/gt2milqsdbk.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.havefunace.top/Article/details/gt2kovvatws.html

[C07] 把函数作为参数传入
来源：http://dali.ivvv.top/Article/details/gt2gpaozdsf.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.sxryk.cn/Article/details/gt2cjpgfsrq.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.cashguo.top/Article/details/gt2zxvcspml.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yuanzhike.top/Article/details/gt2anafipno.html

TS:   arr.map(String)
来源：http://dali.wangdashe.top/Article/details/gt2rdwkzxuo.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.aizwys.cn/Article/details/gt2dmmxrxuf.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhixingplan.top/Article/details/gt2tlmhnlll.html

Ruby: arr.map(&:upcase)
来源：http://dali.hongshengwenyu.top/Article/details/gt2lswssivj.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2xdobvwzi.html

[C08] 闭包
来源：http://dali.yj20258888.top/Article/details/gt2pcuwynaz.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhixingplan.top/Article/details/gt2uzkijykm.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zycfv.cn/Article/details/gt2xmwklduy.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.kuanghao11.cn/Article/details/gt2xlghkltv.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.ydzc1.top/Article/details/gt2ruqyxasn.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.9152youxi.cn/Article/details/gt2tzyljlfz.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.meibo888.top/Article/details/gt2vpbogxct.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.wangdashe.top/Article/details/gt2jlcxmipu.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2monqohli.html

[C09] 递归
来源：http://dali.9152youxi.cn/Article/details/gt2nzjomplh.html


<!-- 参考信息 -->