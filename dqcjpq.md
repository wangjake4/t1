代发 wailian999

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.xuetiantiany.cn/Article/details/gt2afzkxcui.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ocfqtxem.html

TS:   // Node.js：readline 模块
来源：http://dali.gaohongyu789.top/Article/details/gt2pkcsmhmq.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.chenzaomai.com/Article/details/gt2uvlvcvop.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.yueranfly.top/Article/details/gt2ovfeshkv.html

Ruby: gets.chomp
来源：http://dali.kuanghao11.cn/Article/details/gt2mqwwccpk.html

C#:   Console.ReadLine();
来源：http://dali.zycfv.cn/Article/details/gt2rijcynxs.html

[A21] 保留指定小数位输出
来源：http://dali.dianchejie.cn/Article/details/gt2ubuyxuol.html

Py:   f"{3.14159:.2f}"
来源：http://dali.aizwys.cn/Article/details/gt2abtjjdiw.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.0kj1m.cn/Article/details/gt2gmtfwdvt.html

JS:   (3.14159).toFixed(2)
来源：http://dali.c1oappe.top/Article/details/gt2hmgaxeib.html

TS:   (3.14159).toFixed(2)
来源：http://dali.shzxlz.cn/Article/details/gt2pqrscmfe.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.havefunace.top/Article/details/gt2afqmtclb.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.hnxiangtu.top/Article/details/gt2hpxhdwow.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.yonumen.top/Article/details/gt2rcujoisq.html

C#:   3.14159.ToString("F2")
来源：http://dali.316326.xyz/Article/details/gt2lboeeeqo.html

[A22] 获取字符串长度
来源：http://dali.hywenlv.cn/Article/details/gt2uticumwn.html

Py:   len(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2swuhujez.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ixbuunuv.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.feifeiyinyue.top/Article/details/gt2qskraliu.html

TS:   s.length
来源：http://dali.yongpay.top/Article/details/gt2bpfpbeas.html

Java: s.length()
来源：http://dali.wangshuangyany.cn/Article/details/gt2uhijgbwg.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.zycfv.cn/Article/details/gt2fuprjzxy.html

Ruby: s.length
来源：http://dali.hnqzz.top/Article/details/gt2gtyuchod.html

C#:   s.Length
来源：http://dali.0kj1m.cn/Article/details/gt2hxffomog.html

[A23] 大小写转换
来源：http://dali.pengpengdd.cyou/Article/details/gt2stxmvfja.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2dzrjhnsg.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.cqqwz.cn/Article/details/gt2nmmzyxos.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.cucudq.cn/Article/details/gt2hwmhkxpg.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tgtvovmv.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.quarkkingdee.top/Article/details/gt2eozzhijs.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lyrufdyl.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.iojbl.cn/Article/details/gt2ehedkioy.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.smart0.xyz/Article/details/gt2hmwcelld.html

[A24] 去除首尾空白
来源：http://dali.yanxiufei.cn/Article/details/gt2etdnuneb.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.zhixingplan.top/Article/details/gt2nrhjwnru.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.xylfe.cn/Article/details/gt2opunmezs.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yongpay.top/Article/details/gt2fpbyspve.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yuanzhike.top/Article/details/gt2irhsngyo.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.hysaishi.cn/Article/details/gt2vqexzouj.html

Go:   strings.TrimSpace(s)
来源：http://dali.cdnleiting.top/Article/details/gt2ecmxfesv.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.zhixingplan.top/Article/details/gt2czhfgecw.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.wangdashe.top/Article/details/gt2ohuikoyi.html

[A25] 字符串比较
来源：http://dali.iojbl.cn/Article/details/gt2bidszbio.html

Py:   s1 == s2; s1 != s2
来源：http://dali.xuetiantiany.cn/Article/details/gt2suyekphp.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.cucudq.cn/Article/details/gt2awycdmif.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.xziqi.cn/Article/details/gt2vynrmnir.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.daxiang520.top/Article/details/gt2azghexgz.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2suhvbkve.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.haohaochexian.top/Article/details/gt2depgmier.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.ehwqpu.com/Article/details/gt2gprpqeng.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.ppjwa.cn/Article/details/gt2zldzxjld.html

[A26] 类型转换总览
来源：http://dali.ivvv.top/Article/details/gt2ploscert.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.pengpengdd.cyou/Article/details/gt2atznbzms.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.wangshuangyany.cn/Article/details/gt2wtbhyxvc.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.cdnleiting.top/Article/details/gt2pdmoumyw.html

TS:   Number() String() Boolean() x as number
来源：http://dali.jianghu66.top/Article/details/gt2iauaupik.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bqqwkref.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.sxryk.cn/Article/details/gt2zypvstkw.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.svipenyu.cn/Article/details/gt2vxkkkppo.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.hammf.cn/Article/details/gt2irahsphb.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dpxvrmmw.html

B. 流程控制
来源：http://dali.pengpengdd.cyou/Article/details/gt2mejgnnpa.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2lfyydqom.html

[B01] 条件判断 if / else
来源：http://dali.yueranfly.top/Article/details/gt2gcmbclhl.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2utuyknlt.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.nwbrower.top/Article/details/gt2nfuxyiup.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jianghu66.top/Article/details/gt2aejsxiqv.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.xziqi.cn/Article/details/gt2xzidrioi.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.zhoulong.xyz/Article/details/gt2rzfznrsa.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.cucudq.cn/Article/details/gt2gvnoqsnm.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.tanke756.top/Article/details/gt2klpnpghl.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.hammf.cn/Article/details/gt2arscuzlp.html

[B02] 多分支 else if / elif
来源：http://dali.hywenlv.cn/Article/details/gt2fxszyvbg.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.jyoumei.cn/Article/details/gt2gnxizanv.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.jlsjyb.cn/Article/details/gt2dpgabvdc.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cucudq.cn/Article/details/gt2ingepigm.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2afctlorf.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yvedp.cn/Article/details/gt2pzcecsrd.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.daria6918.cn/Article/details/gt2ebuvzkjk.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.dianchejie.cn/Article/details/gt2ntcmmqsh.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.chenjidiqi.icu/Article/details/gt2vzgatyjj.html

[B03] switch / match / case
来源：http://dali.hysaishi.cn/Article/details/gt2jvrxkfeh.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.sweek.top/Article/details/gt2otphjjre.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.jlsjyb.cn/Article/details/gt2chqjotuy.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.shzxlz.cn/Article/details/gt2rmasryne.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.tianlin.xyz/Article/details/gt2relxtgme.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.jyoumei.cn/Article/details/gt2aonckyqs.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.zdqjudy.top/Article/details/gt2xhmuxqvn.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.ivvv.top/Article/details/gt2eqjetkxq.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.jyoumei.cn/Article/details/gt2twlrnumk.html

[B04] for 计数循环
来源：http://dali.jqgfzy.top/Article/details/gt2yvulthly.html

Py:   for i in range(10): print(i)
来源：http://dali.xylfe.cn/Article/details/gt2nobcjzwz.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.gaohongyu789.top/Article/details/gt2kwzmxvjr.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.gogol.net.cn/Article/details/gt2silrpzmn.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yj202588.top/Article/details/gt2rgqjnjbh.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.yuanzhike.top/Article/details/gt2alpwqafp.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.haohaochexian.top/Article/details/gt2thvcixca.html

Ruby: 10.times { |i| puts i }
来源：http://dali.smart0.xyz/Article/details/gt2koaylwbd.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2hetvlpiy.html

[B05] 遍历数组 / 列表
来源：http://dali.yangfankeji.com/Article/details/gt2ioztbabo.html

Py:   for item in arr: print(item)
来源：http://dali.tanke756.top/Article/details/gt2blynptrf.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.zycfv.cn/Article/details/gt2mpzqwkdo.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.tian-w.cn/Article/details/gt2cgorefxs.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.jqgfzy.top/Article/details/gt2qnifdewb.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.yj20258.top/Article/details/gt2hqyslpnq.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.aizwys.cn/Article/details/gt2htxdshbt.html

Ruby: arr.each { |item| puts item }
来源：http://dali.0kj1m.cn/Article/details/gt2nfubpsio.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.yongpay.top/Article/details/gt2opyjfpqf.html

[B06] 遍历字典 / 对象
来源：http://dali.snrcjt.cn/Article/details/gt2tfodkpxu.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.hysaishi.cn/Article/details/gt2fhzjgcjd.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.guannengcc.top/Article/details/gt2rptjpokd.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2rzidlzsh.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.0kj1m.cn/Article/details/gt2wyugxwsw.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2topwvtrv.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yj20258.top/Article/details/gt2pyxovqzs.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.guannengcc.top/Article/details/gt2xaggwrbk.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.wangdashe.top/Article/details/gt2vzugadkx.html

[B07] while 循环
来源：http://dali.hnxiangtu.top/Article/details/gt2ehbbkkyn.html

Py:   while i < 10: i += 1
来源：http://dali.dianchejie.cn/Article/details/gt2fauxeweb.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.mhx1999.top/Article/details/gt2ebbngkzd.html

JS:   while (i < 10) { i++; }
来源：http://dali.zhongyouzk.top/Article/details/gt2qtdquada.html

TS:   while (i < 10) { i++; }
来源：http://dali.nanxinkj.top/Article/details/gt2nqwgaeze.html

Java: while (i < 10) { i++; }
来源：http://dali.kuanghao11.cn/Article/details/gt2txivyzbh.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.cucudq.cn/Article/details/gt2zmhviwco.html

Ruby: while i < 10; i += 1; end
来源：http://dali.vqdsnc.cn/Article/details/gt2hqmzjjxz.html

C#:   while (i < 10) { i++; }
来源：http://dali.yueranfly.top/Article/details/gt2bypchjca.html

[B08] do-while（至少执行一次）
来源：http://dali.zhixingplan.top/Article/details/gt2hbnhywkv.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.bjfxy.top/Article/details/gt2jqhzvubj.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.sxryk.cn/Article/details/gt2yqowxblq.html

JS:   do { i++; } while (i < 10);
来源：http://dali.cashguo.top/Article/details/gt2gnpqiibu.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zhoulong.xyz/Article/details/gt2kkkpjfdy.html

Java: do { i++; } while (i < 10);
来源：http://dali.chenjidiqi.icu/Article/details/gt2ipyshrec.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.gzhubu.top/Article/details/gt2ktcjqguz.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.cheryme.top/Article/details/gt2cbwybalm.html

C#:   do { i++; } while (i < 10);
来源：http://dali.sweek.top/Article/details/gt2xrqzlonc.html

[B09] break 与 continue
来源：http://dali.andypj.xyz/Article/details/gt2ifytlvsb.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uilszert.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.smart0.xyz/Article/details/gt2anehqqbo.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xziqi.cn/Article/details/gt2eyysidsh.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.andypj.xyz/Article/details/gt2gbrfivdn.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.iojbl.cn/Article/details/gt2rlpbexbs.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhengqikj.top/Article/details/gt2fxtiprtv.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.gzhubu.top/Article/details/gt2jcrwekdl.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2qsxtnlca.html

[B10] 遍历同时拿索引
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nhybravj.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.sxryk.cn/Article/details/gt2hgdudsqu.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2wsbrfhsj.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jinqigufen.top/Article/details/gt2oddkrwtm.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.fengsongda.top/Article/details/gt2obhhbukt.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.svipenyu.cn/Article/details/gt2iadanzwk.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.daria6918.cn/Article/details/gt2uwlbczrd.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.316326.xyz/Article/details/gt2dsyjubog.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.pycfn.com/Article/details/gt2mveqameq.html

[B11] 生成数字序列 / 区间
来源：http://dali.9152youxi.cn/Article/details/gt2hjrnhhmx.html

Py:   list(range(0, 10, 2))
来源：http://dali.ivvv.top/Article/details/gt2hzfqkygn.html

PHP:  range(0, 10, 2);
来源：http://dali.smart0.xyz/Article/details/gt2nykxuhcg.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.fengsongda.top/Article/details/gt2maqrdapv.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yueranfly.top/Article/details/gt2mfpgoytq.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.hnxiangtu.top/Article/details/gt2gorhdioq.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.fzhhl.top/Article/details/gt2wzhrevqu.html

Ruby: (0...10).step(2).to_a
来源：http://dali.dashuyun.cn/Article/details/gt2clbcflyu.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.dashuyun.cn/Article/details/gt2yrreeour.html

[B12] 跳出多层循环
来源：http://dali.ivvv.top/Article/details/gt2lxdorrdt.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.ydzc1.top/Article/details/gt2sunaaiqp.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.xylfe.cn/Article/details/gt2hqhovtsc.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhengqikj.top/Article/details/gt2asphncax.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.daxiang520.top/Article/details/gt2oyyyikal.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.sufxvd.cn/Article/details/gt2cihvlnfn.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jyoumei.cn/Article/details/gt2ukrtdbmb.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yuxming.cn/Article/details/gt2ljdlrjmu.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.dashuyun.cn/Article/details/gt2zhkexlzr.html

[B13] 判断是否为数字
来源：http://dali.tian-w.cn/Article/details/gt2jpmipttu.html

Py:   isinstance(x, (int, float))
来源：http://dali.yj20258.top/Article/details/gt2nluyyiym.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zsewvfyw.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.havefunace.top/Article/details/gt2oztzbtjj.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.nanxinkj.top/Article/details/gt2qkckxpzn.html

Java: x instanceof Number
来源：http://dali.meibo888.top/Article/details/gt2hltxfsex.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.cheryme.top/Article/details/gt2wsddobzs.html

Ruby: x.is_a?(Numeric)
来源：http://dali.xylfe.cn/Article/details/gt2bkomcajl.html

C#:   x is int or double or decimal
来源：http://dali.jinqigfzy.top/Article/details/gt2jdimepxo.html

[B14] 判断值是否在集合内
来源：http://dali.jinghuilouyu.cn/Article/details/gt2artnzkir.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yuxming.cn/Article/details/gt2cxvlxfol.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.iojbl.cn/Article/details/gt2ekhfjedy.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.fzhhl.top/Article/details/gt2tpiurejp.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.chenzaomai.com/Article/details/gt2pdarexaw.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.tianlin.xyz/Article/details/gt2bskjyikb.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yj20258888.top/Article/details/gt2kamhcray.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jqgfzy.top/Article/details/gt2xaixhqio.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.iojbl.cn/Article/details/gt2syuvkycm.html

[B15] 布尔运算与取反
来源：http://dali.cashguo.top/Article/details/gt2ctqytwhq.html

Py:   a and b or not c
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vxhbasxg.html

PHP:  $a && $b || !$c
来源：http://dali.hysaishi.cn/Article/details/gt2qvusmivj.html

JS:   a && b || !c
来源：http://dali.daxiang520.top/Article/details/gt2ojbozcqn.html

TS:   a && b || !c
来源：http://dali.jqgfzy.top/Article/details/gt2rxvcwjht.html

Java: a && b || !c
来源：http://dali.redwolf501.top/Article/details/gt2tzvjleji.html

Go:   a && b || !c
来源：http://dali.jlsjyb.cn/Article/details/gt2yqbojwwo.html

Ruby: a && b || !c
来源：http://dali.hysaishi.cn/Article/details/gt2auvswdfp.html

C#:   a && b || !c
来源：http://dali.9152youxi.cn/Article/details/gt2hfktcgnl.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.xylfe.cn/Article/details/gt2ybddjogx.html

Py:   if not data: return
来源：http://dali.nwbrower.top/Article/details/gt2lmfvenkl.html

PHP:  if (!$data) { return; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2zalwogsh.html

JS:   if (!data) return;
来源：http://dali.snrcjt.cn/Article/details/gt2yfkqbonp.html

TS:   if (!data) return;
来源：http://dali.pengpengdd.cyou/Article/details/gt2gdilafmh.html

Java: if (data == null) return;
来源：http://dali.feifeiyinyue.top/Article/details/gt2rhxmmihx.html

Go:   if data == nil { return }
来源：http://dali.zhoulong.xyz/Article/details/gt2qxhucczl.html

Ruby: return if data.nil?
来源：http://dali.tianlin.xyz/Article/details/gt2admbqsss.html

C#:   if (data == null) return;
来源：http://dali.sxryk.cn/Article/details/gt2nmrwqfmf.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2lqkgvckb.html

C. 函数与作用域
来源：http://dali.jinqigufen.top/Article/details/gt2xnyshdqw.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2rmybxfen.html

[C01] 定义函数
来源：http://dali.zhoulong.xyz/Article/details/gt2xsjairky.html

Py:   def add(a, b): return a + b
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rwuvizxg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj20258.top/Article/details/gt2aaiwwqdg.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.sufxvd.cn/Article/details/gt2sxyefcop.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.iojbl.cn/Article/details/gt2rydvndho.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yuxming.cn/Article/details/gt2obgghxqd.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.gaohongyu789.top/Article/details/gt2jrvxwvdg.html

Ruby: def add(a, b); a + b; end
来源：http://dali.iojbl.cn/Article/details/gt2vvrwnsrc.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2gbfumxcl.html

[C02] 默认参数
来源：http://dali.dashuyun.cn/Article/details/gt2kkxdiiwv.html

Py:   def greet(name="World"): return name
来源：http://dali.svipenyu.cn/Article/details/gt2frlazlyr.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hysaishi.cn/Article/details/gt2urocbuud.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2jhjbqzxo.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yj20258.top/Article/details/gt2nyshdath.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zycfv.cn/Article/details/gt2prakrvew.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2oledtlox.html

Ruby: def greet(name = "World") = name
来源：http://dali.tian-w.cn/Article/details/gt2kzqlsvqa.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yuanzhike.top/Article/details/gt2zxmkdwrb.html

[C03] 可变参数
来源：http://dali.zhengqikj.top/Article/details/gt2moeboskp.html

Py:   def total(*args): return sum(args)
来源：http://dali.ppjwa.cn/Article/details/gt2mrhbsglu.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jxubdcql.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2gxpvmxln.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.mhx1999.top/Article/details/gt2pynpoyoz.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.cucudq.cn/Article/details/gt2tinofurm.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.shangyingyoupin.top/Article/details/gt2gkzutoqe.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.dianchejie.cn/Article/details/gt2spwguhdo.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.ehwqpu.com/Article/details/gt2kcxbtpzr.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hltprgvk.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.chenjidiqi.icu/Article/details/gt2cgfoklim.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhongyouzk.top/Article/details/gt2sxljfazc.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.pycfn.com/Article/details/gt2mcizggji.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hnxiangtu.top/Article/details/gt2xnwwfmbx.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhixingplan.top/Article/details/gt2xxxvjeih.html

Go:   // 无：用配置结构体参数
来源：http://dali.daxiang520.top/Article/details/gt2kfqsimza.html

Ruby: f(a: 1, b: 2)
来源：http://dali.andypj.xyz/Article/details/gt2jbkmmjee.html

C#:   f(a: 1, b: 2)
来源：http://dali.ivvv.top/Article/details/gt2lmapjbhm.html

[C05] 返回多个值
来源：http://dali.yangfankeji.com/Article/details/gt2efvqhlmh.html

Py:   return a, b
来源：http://dali.tianlin.xyz/Article/details/gt2gywvjiip.html

PHP:  return [$a, $b];
来源：http://dali.hywenlv.cn/Article/details/gt2okedzeyi.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.hnqzz.top/Article/details/gt2hkxorzqw.html

TS:   return { a, b };
来源：http://dali.dianchejie.cn/Article/details/gt2cmqwoqkt.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nssjmfsn.html

Go:   return a, b
来源：http://dali.aibaodan.cn/Article/details/gt2osbjyjrn.html

Ruby: return a, b
来源：http://dali.yanxiufei.cn/Article/details/gt2ogguvrzu.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.gzhubu.top/Article/details/gt2ywmelgoo.html

[C06] 匿名函数 / lambda
来源：http://dali.sysykeji.top/Article/details/gt2pmmqflio.html

Py:   square = lambda x: x * x
来源：http://dali.jinqigfzy.top/Article/details/gt2wenpoocb.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.redwolf501.top/Article/details/gt2mqsnztrr.html

JS:   const square = x => x * x;
来源：http://dali.yongpay.top/Article/details/gt2oyhwqugq.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.haohaochexian.top/Article/details/gt2rgzfrmka.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lzporhgw.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.gogol.net.cn/Article/details/gt2ylmhiqsa.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhoulong.xyz/Article/details/gt2esgnjias.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zdqjudy.top/Article/details/gt2oyydjkwk.html

[C07] 把函数作为参数传入
来源：http://dali.wangshuangyany.cn/Article/details/gt2otzfmmnj.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.nanxuanxn.top/Article/details/gt2kgljgdsl.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.svipenyu.cn/Article/details/gt2aqemxkke.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.bjfxy.top/Article/details/gt2nntntvpx.html

TS:   arr.map(String)
来源：http://dali.zhixingplan.top/Article/details/gt2adqsgplg.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.nwbrower.top/Article/details/gt2fuhqxoqb.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.tanke756.top/Article/details/gt2mfkpkozw.html

Ruby: arr.map(&:upcase)
来源：http://dali.daxiang520.top/Article/details/gt2zbvsgmwz.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.wangshuangyany.cn/Article/details/gt2agtdyimv.html

[C08] 闭包
来源：http://dali.cucudq.cn/Article/details/gt2ltvsxzyi.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.pengpengdd.cyou/Article/details/gt2ntilycby.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.sxryk.cn/Article/details/gt2zriwvhya.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.ybcxt.top/Article/details/gt2vnmaecty.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.guowangkeji.top/Article/details/gt2ichujkip.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jlsjyb.cn/Article/details/gt2ykbyiaay.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.dashuyun.cn/Article/details/gt2ajnoijio.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.pycfn.com/Article/details/gt2fvpstesg.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.gotoacloud.top/Article/details/gt2rzwqvgrp.html

[C09] 递归
来源：http://dali.aibaodan.cn/Article/details/gt2axsmibmr.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.gotoacloud.top/Article/details/gt2xpfizfqq.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.sweek.top/Article/details/gt2cajvkinl.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.mhx1999.top/Article/details/gt2hbrdavzr.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zdqjudy.top/Article/details/gt2inqzknxk.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.gzhubu.top/Article/details/gt2jebzvpsr.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.iojbl.cn/Article/details/gt2xcgcbmdq.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.daxiang520.top/Article/details/gt2mecbdatc.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.guowangkeji.top/Article/details/gt2blolzkfo.html

[C10] 变量作用域
来源：http://dali.cashguo.top/Article/details/gt2qkqdprev.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ppjwa.cn/Article/details/gt2iuuuajfm.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.c1oappe.top/Article/details/gt2pnoyadca.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.nanxuanxn.top/Article/details/gt2vgaakvcq.html

TS:   同 JS
来源：http://dali.zhoulong.xyz/Article/details/gt2hylvgoon.html

Java: 方法内为块级作用域
来源：http://dali.snrcjt.cn/Article/details/gt2qojbyway.html

Go:   花括号块级作用域
来源：http://dali.daria6918.cn/Article/details/gt2oqvkhito.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.wangdashe.top/Article/details/gt2qobnowqs.html


<!-- 参考信息 -->